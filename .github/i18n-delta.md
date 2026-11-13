# Delta upstream — NuvioMobile

- Gerado em: 2026-11-13T19:28:05.0837481+00:00
- Base local: e9f136bc7cc1694be1413db0dba61292bd3eb047
- Upstream: upstream/cmp-rewrite / 4af1db91696cf76f0729aa5111d7b9532b523dba
- Chaves pendentes: 15

## Chaves detectadas

```json
{
  "tool": "sync-check.ps1",
  "version": "1.0.0",
  "generatedAt": "2026-11-13T19:28:04.6764689+00:00",
  "root": "D:\\a\\NuvioMobile",
  "mode": "nofetch",
  "summary": {
    "analyzed": 1,
    "updated": 0,
    "newStrings": 1,
    "removals": 0,
    "gaps": 0,
    "errors": 0,
    "pendingKeys": 15,
    "missingKeys": 0
  },
  "baselineUpdated": [],
  "repos": [
    {
      "name": "NuvioMobile",
      "branch": "cmp-rewrite",
      "head": "4064b725c601a5b216215544a5937b65eda8d6b2",
      "headShort": "4064b725",
      "upstreamRef": "upstream/cmp-rewrite",
      "upstreamCommit": "4af1db91696cf76f0729aa5111d7b9532b523dba",
      "baseCommit": "e9f136bc7cc1694be1413db0dba61292bd3eb047",
      "baseSource": "baseline",
      "ahead": 8,
      "behind": 41,
      "status": "Novas strings",
      "added": 15,
      "modified": 0,
      "removed": 0,
      "pending": 15,
      "baseKeys": 2738,
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
          "baseKeys": 2514,
          "upstreamKeys": 2529,
          "added": [
            "player_error_source_startup_timeout",
            "settings_continue_watching_click_action_description",
            "settings_continue_watching_click_action_details",
            "settings_continue_watching_click_action_details_desc",
            "settings_continue_watching_click_action_details_upcoming",
            "settings_continue_watching_click_action_details_upcoming_desc",
            "settings_continue_watching_click_action_stream",
            "settings_continue_watching_click_action_stream_desc",
            "settings_continue_watching_click_action_title",
            "settings_playback_auto_switch_engine_blocked_by_fallback",
            "settings_playback_fallback_max_sources",
            "settings_playback_fallback_next_source",
            "settings_playback_fallback_next_source_blocked_by_engine_switch",
            "settings_playback_fallback_next_source_description",
            "settings_playback_fallback_startup_timeout"
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

# Localização pt-BR — NuvioMobile (delta `sync-check`)

**Nota de método:** o delta lista 15 chaves novas, mas o conteúdo EN de cada uma não veio no JSON. Seguindo o AGENTS.md §3 (nunca traduzir chave isolada; reconstruir o eixo pela família), inferi o eixo pelas famílias `settings_playback_fallback_*`, `settings_continue_watching_click_action_*` e `player_error_*`, e pelas chaves irmãs já existentes no repositório. **As colunas "EN" abaixo são reconstruções do texto provável a partir do nome da chave — precisam ser conferidas contra `values/strings.xml` antes do merge.** Onde o texto EN real divergir, a sugestão pt-BR deve ser reavaliada.

## Tabela de handoff (§8)

| chave | EN (reconstruído) | sugestão pt-BR | justificativa |
| --- | --- | --- | --- |
| `player_error_source_startup_timeout` | Source startup timed out | A fonte demorou para iniciar | Família `player_error_*` = mensagem de erro no player. Eixo: falha de inicialização da fonte. "Timed out" literal ("tempo esgotado") é decalque; o cinéfilo lê "demorou para iniciar". ≤ 100 chars. |
| `settings_continue_watching_click_action_description` | Action when tapping a Continue Watching item | Ação ao tocar em um item de Continuar assistindo | Família `settings_continue_watching_click_action_*` = configuração do comportamento de clique. "Continuar assistindo" é o rótulo consolidado de mercado (Netflix, Prime Video, Disney+). |
| `settings_continue_watching_click_action_details` | Open details | Abrir detalhes | Opção de ação no eixo de clique. Infinitivo (§5). Rótulo curto de opção de configuração. |
| `settings_continue_watching_click_action_details_desc` | Opens the title details page | Abre a página de detalhes do título | Descrição da opção acima. Caixa de frase, sem ponto final. |
| `settings_continue_watching_click_action_details_upcoming` | Open details (upcoming) | Abrir detalhes (em breve) | Variante para títulos ainda não lançados. "Em breve" é o rótulo de mercado para conteúdo futuro (Netflix/Prime). |
| `settings_continue_watching_click_action_details_upcoming_desc` | Opens the details page for upcoming titles | Abre a página de detalhes de títulos em breve | Descrição da variante. Mantém consistência com a chave anterior. |
| `settings_continue_watching_click_action_stream` | Play / Stream | Assistir | Opção de ação: iniciar reprodução. "Assistir" é o verbo de mercado para play em contexto de catálogo (Netflix usa "Assistir", Prime "Reproduzir"). Escolhi "Assistir" por ser o rótulo dominante em trackers/streaming BR; "Reproduzir" fica como alternativa. |
| `settings_continue_watching_click_action_stream_desc` | Starts playback of the title | Inicia a reprodução do título | Descrição da opção. "Reprodução" como substantivo é padrão em players (VLC, YouTube BR). |
| `settings_continue_watching_click_action_title` | Continue Watching tap action | Ação ao tocar em Continuar assistindo | Título da seção de configuração. ≤ 32 chars? — "Ação ao tocar em Continuar assistindo" tem 37; **encurtar para "Ação de clique em Continuar assistindo" (36) ainda estoura**. Sugestão final: **"Ação ao tocar em Continuar assistindo"** — se o slot exigir ≤ 32, usar **"Ação em Continuar assistindo"** (28). Verificar no consumidor (§3.3). |
| `settings_playback_auto_switch_engine_blocked_by_fallback` | Auto engine switch blocked by fallback | Troca automática de motor bloqueada pelo fallback | Família `settings_playback_*` = configurações de reprodução. "Motor" = engine de player (termo usado em players BR: "motor de vídeo"). "Fallback" mantido — é jargão técnico já absorvido; alternativa "reserva" perde precisão. |
| `settings_playback_fallback_max_sources` | Max fallback sources | Máximo de fontes reserva | Eixo: limite de fontes no fallback. "Fontes reserva" traduz fallback sem decalque. ≤ 32. |
| `settings_playback_fallback_next_source` | Next source | Próxima fonte | Rótulo de ação/estado no fallback. Curto, padrão de player. |
| `settings_playback_fallback_next_source_blocked_by_engine_switch` | Next source blocked by engine switch | Próxima fonte bloqueada pela troca de motor | Estado (particípio "bloqueada"), não gerúndio (§5). Consistente com "motor" acima. |
| `settings_playback_fallback_next_source_description` | Description of next source fallback | Passa para a próxima fonte quando a atual falha | Descrição. Verbo no presente do indicativo em descrição de comportamento é aceitável; alternativa "Avança para a próxima fonte..." — escolhi "Passa para" por fluidez. ≤ 100. |
| `settings_playback_fallback_startup_timeout` | Fallback startup timeout | Tempo limite de início do fallback | Eixo: timeout de inicialização no fallback. "Tempo limite" é o termo de mercado para timeout em UI BR (Android, Windows). Evita "timeout" cru. |

## Observações de conformidade

- **Placeholders:** nenhuma das 15 chaves aparenta ter `%1$s`/`%1$d`; se houver no EN real, preservar intacto (§4).
- **Marcas:** nenhuma chave toca `Nuvio TV`, `Trakt TV`, `MDBList`, `Bingers`.
- **Família de status:** este delta não inclui chaves `movie_status_*`/`show_status_*`; a consistência de status não é afetada.
- **Limite de badge (≤14):** nenhuma chave é badge; todas são rótulo/descrição de configuração ou erro de player.
- **`values-pt`:** não tocado (§4, §6).
- **Pendência crítica:** confirmar o texto EN real de cada chave em `values/strings.xml` e o slot no consumidor (`grep` em `composeApp/src`) antes de aplicar — especialmente `settings_continue_watching_click_action_title`, cujo limite de 32 pode exigir a forma curta.

## Alternativas rejeitadas (registro §3.6)

| chave | alternativa rejeitada | motivo |
| --- | --- | --- |
| `player_error_source_startup_timeout` | "Tempo esgotado ao iniciar a fonte" | Decalque de "timed out"; soa técnico demais para erro de player. |
| `settings_continue_watching_click_action_stream` | "Reproduzir" | Válido, mas "Assistir" é o rótulo dominante em catálogo de streaming BR; "Reproduzir" fica reservado a controles de player. |
| `settings_playback_auto_switch_engine_blocked_by_fallback` | "Troca automática de mecanismo bloqueada pela reserva" | "Mecanismo" é genérico; "motor" é o termo de player. "Reserva" perde a noção de fallback técnico. |
| `settings_playback_fallback_startup_timeout` | "Timeout de inicialização do fallback" | Anglicismo desnecessário quando "tempo limite" é padrão de UI BR. |

> Revise as sugestões e aplique apenas as chaves listadas, seguindo o AGENTS.md local. Este PR não altera os catálogos automaticamente.
