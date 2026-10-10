# Perfis de marca

## RD Station (TOTVS) — perfil padrão desta skill

Arquivo: [`skills/diagram-design/references/profile-rd-station.md`](../../skills/diagram-design/references/profile-rd-station.md). A skill já usa este perfil por padrão: basta instalar (`npx skills add luisjlourenco/diagram`) e pedir um diagrama. Para voltar à paleta original, peça "default skin".

Skin do Diagram Design com os tokens do Tangram, o design system da RD Station.

| Papel | Claro | Escuro |
|---|---|---|
| `paper` | `#f5f7f8` | `#001927` (navy RD) |
| `ink` | `#002233` | `#f5f7f8` |
| `muted` | `#405466` | `#b2bcc1` |
| `accent` | `#005580` + wash ciano `#00DBFF` | `#00dbff` (ciano RD) |
| `link` | `#6e00c5` | `#b570ff` |
| Tipografia | DM Sans (títulos e nomes) + Geist Mono (rótulos técnicos) | idem |

Todos os papéis passam no contrato de contraste (`python3 scripts/verify-contrast.py --style-guide skills/diagram-design/references/profile-rd-station.md`).

### Outros projetos com outra marca

Para fixar um perfil diferente num projeto, crie na raiz dele um arquivo `.diagram-design` com `profile: <slug>` (ver `references/profiles.md`).

Exemplos renderizados: [`rd-station-examples/`](rd-station-examples/).
