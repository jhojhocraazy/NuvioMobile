# Delta upstream — NuvioMobile

- Gerado em: 2026-11-21T14:30:38.1377980+00:00
- Base local: 4af1db91696cf76f0729aa5111d7b9532b523dba
- Upstream: upstream/cmp-rewrite / c5a73772fa768574920abde6440b257f18950079
- Chaves pendentes: 89

## Chaves detectadas

```json
{
  "tool": "sync-check.ps1",
  "version": "1.0.0",
  "generatedAt": "2026-11-21T14:30:37.5283993+00:00",
  "root": "D:\\a\\NuvioMobile",
  "mode": "nofetch",
  "summary": {
    "analyzed": 1,
    "updated": 0,
    "newStrings": 1,
    "removals": 0,
    "gaps": 0,
    "errors": 0,
    "pendingKeys": 89,
    "missingKeys": 0
  },
  "baselineUpdated": [],
  "repos": [
    {
      "name": "NuvioMobile",
      "branch": "cmp-rewrite",
      "head": "2fdd7197cfdc772db6397f25ad8b823258a361b1",
      "headShort": "2fdd7197",
      "upstreamRef": "upstream/cmp-rewrite",
      "upstreamCommit": "c5a73772fa768574920abde6440b257f18950079",
      "baseCommit": "4af1db91696cf76f0729aa5111d7b9532b523dba",
      "baseSource": "baseline",
      "ahead": 15,
      "behind": 175,
      "status": "Novas strings",
      "added": 77,
      "modified": 12,
      "removed": 5,
      "pending": 89,
      "baseKeys": 2753,
      "missingKeys": 0,
      "extraKeys": 5,
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
          "upstreamKeys": 2546,
          "added": [
            "addons_tracking_consent_body",
            "addons_tracking_consent_checkbox",
            "addons_tracking_consent_title",
            "downloads_delete_message",
            "downloads_delete_title",
            "downloads_downloading_count",
            "downloads_empty_message",
            "downloads_episodes",
            "downloads_pause_all",
            "downloads_resume_all",
            "downloads_section_downloaded",
            "downloads_speed",
            "downloads_titles",
            "downloads_watched_count",
            "library_filter_genre",
            "library_filter_watched",
            "library_filter_year",
            "library_type_all",
            "library_watched_filter_all",
            "library_watched_filter_unwatched",
            "library_watched_filter_watched",
            "subtitle_outline_width"
          ],
          "modified": [
            "cloud_library_select_provider",
            "cloud_library_select_type",
            "library_filter_all_types",
            "library_filter_list",
            "library_filter_sort",
            "library_filter_type",
            "library_sort_added_asc",
            "library_sort_added_desc",
            "library_sort_provider_order",
            "library_sort_released_asc",
            "library_sort_released_desc"
          ],
          "removed": [
            "downloads_empty_episodes",
            "downloads_episode_count",
            "downloads_section_movies",
            "downloads_section_shows",
            "downloads_status_completed"
          ],
          "missing": [],
          "extra": [
            "downloads_empty_episodes",
            "downloads_episode_count",
            "downloads_section_movies",
            "downloads_section_shows",
            "downloads_status_completed"
          ],
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
          "upstreamKeys": 115,
          "added": [
            "plex_add_description",
            "plex_browser_waiting",
            "plex_code_expired",
            "plex_code_instructions",
            "plex_code_starting",
            "plex_code_waiting",
            "plex_continue",
            "plex_new_code",
            "plex_reach_local",
            "plex_reach_offline_detail",
            "plex_reach_relay_detail",
            "plex_reach_remote",
            "plex_server_owned",
            "plex_server_shared",
            "plex_servers_checking",
            "plex_servers_finding",
            "plex_servers_none",
            "plex_servers_subtitle",
            "plex_servers_title",
            "plex_sign_in_subtitle",
            "plex_use_browser",
            "plex_use_code",
            "plex_user_admin",
            "plex_user_managed",
            "plex_users_subtitle",
            "plex_users_title",
            "servers_code_copied",
            "servers_failure_remote_playback",
            "servers_has_pin",
            "servers_pin_hint",
            "servers_pin_title",
            "servers_pin_wrong",
            "servers_signing_in",
            "silo_add_description",
            "silo_address_hint",
            "silo_address_subtitle",
            "silo_approve_in_browser",
            "silo_code_denied",
            "silo_code_expired",
            "silo_code_instructions",
            "silo_code_starting",
            "silo_code_subtitle",
            "silo_code_unavailable",
            "silo_code_waiting",
            "silo_error_not_silo",
            "silo_error_password_off",
            "silo_error_temporary_password",
            "silo_error_too_many_tries",
            "silo_finding",
            "silo_new_code",
            "silo_password_subtitle",
            "silo_profile_kids",
            "silo_profiles_title",
            "silo_use_code",
            "silo_use_password"
          ],
          "modified": [
            "settings_content_discovery_media_servers_description"
          ],
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

**Escopo:** apenas as 1 chave nova listada em `summary.newStrings` (`subtitle_outline_width`, em `values/strings.xml`). As demais chaves `added`/`modified` do delta já constam como pendentes no baseline (`pendingKeys: 89`) e não foram solicitadas nesta rodada.

**Família/eixo inferido:** `subtitle_*` — eixo de **configuração de aparência de legenda** (contorno/borda do texto). Não é status, não é ação de fluxo; é rótulo de ajuste numérico/controle deslizante. Limite aplicável: rótulo de seção ≤ 32 caracteres.

| chave | EN | sugestão pt-BR | justificativa |
| --- | --- | --- | --- |
| `subtitle_outline_width` | Subtitle outline width | Espessura do contorno | Família `subtitle_*` = aparência de legenda; "outline" aqui é a borda que envolve o texto, não "esboço/resumo". Em pt-BR de players (VLC, MX Player, Plex) o controle equivalente aparece como "espessura"/"largura do contorno"; "espessura" é o termo natural para traço de borda e evita o decalque "largura do esboço". 22 caracteres, dentro do limite de 32. Alternativa rejeitada: "Largura do contorno" (literal, defensável mas menos fluida) e "Contorno da legenda" (perde a noção de medida do controle). |

**Observações de conformidade**
- Nenhum placeholder na string; nada a preservar.
- Nenhuma marca de serviço envolvida.
- Sem ponto final (rótulo de ajuste), caixa de frase.
- Consistência: usar "contorno" para `outline` em toda a família `subtitle_*` quando as chaves irmãs forem traduzidas.

**Handoff (formato §8)**

| chave | EN | família/eixo inferido | pt-BR escolhido | evidência | alternativa rejeitada | motivo |
| --- | --- | --- | --- | --- | --- | --- |
| `subtitle_outline_width` | Subtitle outline width | `subtitle_*` — aparência de legenda (borda do texto) | Espessura do contorno | Rótulos de controle de legenda em players de mercado (VLC, MX Player, Plex) usam "espessura"/"contorno" para borda de texto | "Largura do contorno"; "Contorno da legenda" | "Espessura" é o termo corrente para traço de borda; "largura" soa decalque de *width*; "contorno da legenda" perde a noção de medida do slider |

> Revise as sugestões e aplique apenas as chaves listadas, seguindo o AGENTS.md local. Este PR não altera os catálogos automaticamente.
