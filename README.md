# space-assets

Repositório público de imagens para tasks do ClickUp (specs de PO / Tech Lead).

## Estrutura

```
{projeto}/{task-slug}/
├── 01-listagem.png
├── 02-formulario.png
└── ...
```

**Exemplos:**

```
bateu/pixels-platform-affiliate/01-listagem.png
monitor/dashboard-filters/01-sidebar.png
```

## URL para markdown (ClickUp)

```
https://raw.githubusercontent.com/Space-Software-LTDA/space-assets/main/{projeto}/{task-slug}/{arquivo}.png
```

**Exemplo:**

```markdown
![Listagem de pixels](https://raw.githubusercontent.com/Space-Software-LTDA/space-assets/main/bateu/pixels-platform-affiliate/01-listagem.png)
```

## Convenção de nomes

- Pasta: `{projeto}/{task-slug}` — slug em kebab-case, alinhado ao arquivo `task-*.md`
- Arquivo: `{ordem}-{tela-ou-estado}.png` — ex.: `03-combobox-abiliado-aberto.png`

## Quem mantém

Gerado automaticamente pelo agente PO/Tech Lead ao criar tasks com referência visual.
