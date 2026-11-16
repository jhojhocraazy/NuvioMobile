# Delta upstream — NuvioMobile

- Gerado em: 2026-11-16T15:32:11.4244610+00:00
- Base local: 4af1db91696cf76f0729aa5111d7b9532b523dba
- Upstream: upstream/cmp-rewrite / fc05fe8e516a5bd749c8a4e7b1c05143acd3f031
- Chaves pendentes: 11

## Chaves detectadas

```json
{
  "tool": "sync-check.ps1",
  "version": "1.0.0",
  "generatedAt": "2026-11-16T15:32:10.8064704+00:00",
  "root": "D:\\a\\NuvioMobile",
  "mode": "nofetch",
  "summary": {
    "analyzed": 1,
    "updated": 0,
    "newStrings": 1,
    "removals": 0,
    "gaps": 0,
    "errors": 0,
    "pendingKeys": 11,
    "missingKeys": 0
  },
  "baselineUpdated": [],
  "repos": [
    {
      "name": "NuvioMobile",
      "branch": "cmp-rewrite",
      "head": "3b1ef53582938af7cb099ad343cb9cc39c26432c",
      "headShort": "3b1ef535",
      "upstreamRef": "upstream/cmp-rewrite",
      "upstreamCommit": "fc05fe8e516a5bd749c8a4e7b1c05143acd3f031",
      "baseCommit": "4af1db91696cf76f0729aa5111d7b9532b523dba",
      "baseSource": "baseline",
      "ahead": 13,
      "behind": 117,
      "status": "Novas strings",
      "added": 11,
      "modified": 0,
      "removed": 0,
      "pending": 11,
      "baseKeys": 2753,
      "missingKeys": 0,
      "extraKeys": 0,
      "coveragePercent": 100.0,
      "dirtyFiles": [],
      "sourceDirty": [],
      "fetchError": "",
      "error": "",
      "warnings": [
        "Modo offline (-NoFetch): git fetch não executado."
      ],
      "files": [
        {
          "path": "composeApp/src/commonMain/composeResources/values/autosync_strings.xml",
          "target": "composeApp/src/commonMain/composeResources/values-pt-rBR/autosync_strings.xml",
          "targetExists": true,
          "baseKeys": 10,
          "upstreamKeys": 10,
          "added": [],
          "modified": [],
          "removed": [],
          "missing": [],
          "extra": [],
          "warning": ""
        },
        {
          "path": "composeApp/src/commonMain/composeResources/values/autosync_toast_strings.xml",
          "target": "composeApp/src/commonMain/composeResources/values-pt-rBR/autosync_toast_strings.xml",
          "targetExists": true,
          "baseKeys": 2,
          "upstreamKeys": 2,
          "added": [],
          "modified": [],
          "removed": [],
          "missing": [],
          "extra": [],
          "warning": ""
        },
        {
          "path": "composeApp/src/commonMain/composeResources/values/strings.xml",
          "target": "composeApp/src/commonMain/composeResources/values-pt-rBR/strings.xml",
          "targetExists": true,
          "baseKeys": 2529,
          "upstreamKeys": 2540,
          "added": [
            "addons_tracking_consent_body",
            "addons_tracking_consent_checkbox",
            "addons_tracking_consent_title",
            "library_filter_genre",
            "library_filter_watched",
            "library_filter_year",
            "library_type_all",
            "library_watched_filter_all",
            "library_watched_filter_unwatched",
            "library_watched_filter_watched",
            "subtitle_outline_width"
          ],
          "modified": [],
          "removed": [],
          "missing": [],
          "extra": [],
          "warning": ""
        },
        {
          "path": "composeApp/src/commonMain/composeResources/values/strings_mdblist.xml",
          "target": "composeApp/src/commonMain/composeResources/values-pt-rBR/strings_mdblist.xml",
          "targetExists": true,
          "baseKeys": 52,
          "upstreamKeys": 52,
          "added": [],
          "modified": [],
          "removed": [],
          "missing": [],
          "extra": [],
          "warning": ""
        },
        {
          "path": "composeApp/src/commonMain/composeResources/values/strings_party.xml",
          "target": "composeApp/src/commonMain/composeResources/values-pt-rBR/strings_party.xml",
          "targetExists": true,
          "baseKeys": 84,
          "upstreamKeys": 84,
          "added": [],
          "modified": [],
          "removed": [],
          "missing": [],
          "extra": [],
          "warning": ""
        },
        {
          "path": "composeApp/src/commonMain/composeResources/values/strings_pip.xml",
          "target": "composeApp/src/commonMain/composeResources/values-pt-rBR/strings_pip.xml",
          "targetExists": true,
          "baseKeys": 1,
          "upstreamKeys": 1,
          "added": [],
          "modified": [],
          "removed": [],
          "missing": [],
          "extra": [],
          "warning": ""
        },
        {
          "path": "composeApp/src/commonMain/composeResources/values/strings_ratings.xml",
          "target": "composeApp/src/commonMain/composeResources/values-pt-rBR/strings_ratings.xml",
          "targetExists": true,
          "baseKeys": 15,
          "upstreamKeys": 15,
          "added": [],
          "modified": [],
          "removed": [],
          "missing": [],
          "extra": [],
          "warning": ""
        },
        {
          "path": "composeApp/src/commonMain/composeResources/values/strings_servers.xml",
          "target": "composeApp/src/commonMain/composeResources/values-pt-rBR/strings_servers.xml",
          "targetExists": true,
          "baseKeys": 60,
          "upstreamKeys": 60,
          "added": [],
          "modified": [],
          "removed": [],
          "missing": [],
          "extra": [],
          "warning": ""
        }
      ]
    }
  ]
}

```

## Sugestões DeepSeek

# Localização pt-BR — NuvioMobile (11 chaves novas)

**Nota de método:** o delta JSON lista as chaves, mas não traz o texto EN nem o código consumidor. Segui o protocolo do AGENTS.md (§3) reconstruindo as famílias (`library_filter_*`, `library_watched_filter_*`, `library_type_*`, `addons_tracking_consent_*`, `subtitle_outline_width`) e aplicando os limites do §5. Onde a evidência de mercado é citada, ela vem do vocabulário consolidado de trackers/streaming (Trakt, Letterboxd, Netflix, Prime Video, Disney+). **Recomendo confirmar cada linha com `grep` no consumidor antes do commit** — em especial `subtitle_outline_width`, cujo slot (rótulo de slider vs. descrição) muda o limite.

| chave | EN (inferido) | sugestão pt-BR | justificativa |
| --- | --- | --- | --- |
| `addons_tracking_consent_title` | Tracking consent | Consentimento de rastreio | Título de seção (≤32). "Rastreio" é o termo de mercado para *tracking* em apps de mídia; "rastreamento" é mais longo e soa técnico. |
| `addons_tracking_consent_body` | (texto explicativo) | Ao ativar, seus dados de exibição são enviados aos serviços de rastreio conectados. | Descrição (≤100). Frase corrida, sem decalque de "By enabling…". Preserva nomes de serviço intactos. |
| `addons_tracking_consent_checkbox` | I agree / Enable tracking | Concordo em compartilhar meus dados | Rótulo de checkbox; ação em 1ª pessoa é padrão de consentimento (LGPD/GDPR). Alternativa rejeitada: "Ativar rastreio" — ambíguo sobre o que se ativa. |
| `library_filter_genre` | Genre | Gênero | Filtro de biblioteca; termo consolidado em Netflix/Prime/Trakt pt-BR. |
| `library_filter_year` | Year | Ano | Idem; curto, cabe em chip. |
| `library_filter_watched` | Watched | Assistidos | **Eixo de estado de visualização** (família `library_watched_filter_*`). Particípio/adjetivo conforme §5. "Assistidos" concorda com "títulos" implícito; alternativa rejeitada: "Vistos" (ambíguo com "visto" de visto de viagem) e "Já assisti" (verbo, quebra o eixo). |
| `library_watched_filter_all` | All | Todos | Posição do eixo: sem filtro de estado. Consistente com `library_type_all`. |
| `library_watched_filter_watched` | Watched | Assistidos | Mesma palavra de `library_filter_watched` — consistência obrigatória (§5). |
| `library_watched_filter_unwatched` | Unwatched | Não assistidos | Contraste direto do eixo. Alternativa rejeitada: "A assistir" (implica fila, não estado) e "Pendentes" (jargão de tarefa). |
| `library_type_all` | All | Todos | Fecha o eixo de tipo (filmes/séries/todos). Mesma palavra de `library_watched_filter_all`. |
| `subtitle_outline_width` | Outline width | Espessura do contorno | Rótulo de configuração de legenda. "Contorno" é o termo de mercado (Netflix/YouTube pt-BR usam "contorno" para *outline* de legenda). Se for descrição de slider, cabe; se for chip, encurtar para "Contorno". |
| *(11ª chave — ver nota)* | — | — | O delta lista 11 `added`, mas só 10 aparecem no array `added` de `strings.xml`; a 11ª (`subtitle_outline_width`) fecha a contagem. Nenhuma chave órfã detectada. |

## Handoff (§8)

| chave | EN | família/eixo inferido | pt-BR escolhido | evidência | alternativa rejeitada | motivo |
| --- | --- | --- | --- | --- | --- | --- |
| `library_filter_watched` | Watched | `library_watched_filter_*` — estado de visualização (assistido/não assistido/todos) | Assistidos | Trakt pt-BR ("Assistidos"), Letterboxd pt-BR | "Vistos" | Ambiguidade lexical; "assistidos" é o termo de tracker. |
| `library_watched_filter_unwatched` | Unwatched | mesmo eixo, polo negativo | Não assistidos | Trakt pt-BR, Netflix "Não assistidos" | "Pendentes" | Jargão de tarefa, não de mídia. |
| `library_watched_filter_all` / `library_type_all` | All | eixo de filtro, posição neutra | Todos | Netflix/Prime pt-BR | "Tudo" | "Todos" concorda com "títulos" implícito. |
| `addons_tracking_consent_*` | Tracking consent | fluxo de consentimento de addons de rastreio | Consentimento de rastreio / Concordo em compartilhar meus dados | LGPD, padrão de consent banner | "Ativar rastreio" | Não descreve o que se ativa. |
| `subtitle_outline_width` | Outline width | configuração de aparência de legenda | Espessura do contorno | Netflix pt-BR ("contorno"), YouTube | "Largura do contorno" | "Largura" sugere dimensão horizontal; "espessura" é o correto para stroke. |

## Pendências de verificação

1. **Texto EN real** das 11 chaves não veio no delta — as sugestões acima são reconstruídas por família. Rodar `grep -n "addons_tracking_consent_body\|subtitle_outline_width" composeApp/src/commonMain/composeResources/values/strings.xml` para confirmar.
2. **Slot de `subtitle_outline_width`**: se for chip (≤14), trocar para "Contorno"; se for rótulo de slider, "Espessura do contorno" (21) cabe.
3. **`addons_tracking_consent_body`**: se o EN citar serviços específicos (Trakt, MDBList), mantê-los intactos e ajustar a frase.
4. **Paridade**: `values-pt` (não-brasileira) não foi tocada, conforme §4.

> Revise as sugestões e aplique apenas as chaves listadas, seguindo o AGENTS.md local. Este PR não altera os catálogos automaticamente.
