# Perfis de marca

## RD Station (TOTVS) — `rd-station.md`

Skin do Diagram Design com os tokens do Tangram, o design system da RD Station.

| Papel | Claro | Escuro |
|---|---|---|
| `paper` | `#f5f7f8` | `#001927` (navy RD) |
| `ink` | `#002233` | `#f5f7f8` |
| `muted` | `#405466` | `#b2bcc1` |
| `accent` | `#005580` + wash ciano `#00DBFF` | `#00dbff` (ciano RD) |
| `link` | `#6e00c5` | `#b570ff` |
| Tipografia | DM Sans (títulos e nomes) + Geist Mono (rótulos técnicos) | idem |

Todos os papéis passam no contrato de contraste (`python3 scripts/verify-contrast.py --style-guide docs/profiles/rd-station.md`).

### Instalar na sua máquina

```bash
mkdir -p ~/.diagram-design/profiles
curl -fsSL https://raw.githubusercontent.com/luisjlourenco/diagram/claude/epic-wozniak-afzvs0/docs/profiles/rd-station.md \
  -o ~/.diagram-design/profiles/rd-station.md
```

Depois, no agente: *"diagram-design: load rd-station"* (aplica a todos os diagramas). Para fixar a marca só num projeto, crie na raiz dele um arquivo `.diagram-design` com:

```text
profile: rd-station
```

Exemplos renderizados: [`rd-station-examples/`](rd-station-examples/).
