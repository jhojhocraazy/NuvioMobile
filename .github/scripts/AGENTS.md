# AGENTS.md — Diretriz local de localização: NuvioMobile

## 1. Domínio

Central multimídia multi-plataforma em Compose Multiplatform (Android e iOS) que agrega catálogo,
player próprio e serviços de rastreio/curadoria: Nuvio TV, Trakt TV, MDBList e Bingers, conectados por
uma camada de sincronização.

O usuário é cinéfilo que mantém histórico e listas de títulos em tracker. Ele compara o app com
plataformas de streaming e com trackers consolidados; a expectativa de vocabulário vem dessas telas,
não de um manual de tradução.

## 2. Onde o texto vive (verificado no clone)

| Caminho | Papel |
| --- | --- |
| `composeApp/src/commonMain/composeResources/values/strings.xml` | fonte EN |
| `composeApp/src/commonMain/composeResources/values-pt/strings.xml` | variante não-brasileira |
| `composeApp/src/commonMain/composeResources/values-pt-rBR/strings.xml` | alvo pt-BR (já existe) |
| `composeApp/src/.../` | código Kotlin; texto hardcoded ali é bug de i18n |
| `iosApp/` | casca iOS; strings vêm do Compose |

Fato estrutural: `values/strings.xml` contém famílias de chaves por eixo, por exemplo o conjunto
`movie_status_*`, cujos membros compartilham um mesmo campo de exibição (badge de status na tela do
título). A família é a pista de contexto mais confiável do projeto.

## 3. Protocolo de inferência semântica

1. **Nunca traduzir chave isolada.** Uma chave de status é uma posição num eixo, não uma palavra.
2. **Reconstruir o eixo pela família.** Liste todas as chaves irmãs (`movie_status_*`, `show_status_*`,
   equivalentes de temporada e episódio) e leia o `values/strings.xml` inteiro. O contraste entre os
   membros revela se o eixo é janela de lançamento, estado temporal, disponibilidade ou etapa de
   fluxo. Só depois escolha o termo.
3. **Confirmar no consumidor.** `grep` pela chave em `composeApp/src` para ver o componente, o slot e
   o espaço disponível. Um badge de 14 caracteres não aceita a tradução "correta" de 25.
4. **Buscar evidência de mercado.** Como os apps de streaming e os trackers usados pelo público
   brasileiro rotulam esse mesmo estado? Cite a fonte consultada; intuição não conta como evidência.
5. **Testar fluidez.** Leia como se estivesse navegando rápido. Se a palavra parece tradução de
   palavra, refaça.
6. **Registrar** termo, evidência e alternativa rejeitada.

## 4. Invariantes técnicas

- `%1$s`, `%1$d`, `&amp;`, `\'` e nomes de campo de API (`tmdb_id`, `imdb_id`) intactos.
- `values-pt` (variante não-brasileira) não é fonte de verdade para pt-BR; é registro separado.
- Nomes de serviço não se traduzem nem se flexionam.
- Nenhuma chave nova sem par no `values/`; nenhuma string de UI criada em Kotlin.

## 5. Critérios de aceitação

- Badge/chip ≤ 14 caracteres; rótulo de seção ≤ 32; descrição ≤ 100.
- Caixa de frase, sem ponto final em título de seção.
- Ação no infinitivo; estado no particípio/adjetivo, nunca em gerúndio.
- Consistência: o mesmo estado tem a mesma palavra em toda a árvore de recursos.
- Zero decalque de estrutura inglesa.

## 6. Proibições

- **Tradução literal crua de chave de status.** É a falha mais grave deste repositório: produz termo
  tecnicamente defensável e visualmente errado.
- Escolher termo por dicionário sem reconstruir o eixo da família de chaves.
- Traduzir `Nuvio TV`, `Trakt TV`, `MDBList`, `Bingers`.
- Tocar em `values-pt` como se fosse pt-BR.
- Criar string fora de `composeResources/values*`.

## 7. Verificação

```bash
pwsh -c "[xml](Get-Content -Raw 'composeApp/src/commonMain/composeResources/values-pt-rBR/strings.xml') | Out-Null"
./gradlew :composeApp:compileDebugKotlinAndroid   # quando o SDK estiver disponível
```

Checklist: paridade de chaves, placeholders, limites de badge, marcas intactas, família de status
coerente entre si.

## 8. Handoff

| chave | EN | família/eixo inferido | pt-BR escolhido | evidência | alternativa rejeitada | motivo |
| --- | --- | --- | --- | --- | --- | --- |

Sem a coluna "família/eixo inferido", a decisão de status é considerada não fundamentada.
