# My Wiki

A semantic markdown knowledge base powered by the Wiki CLI.

## Workspace Layout

- `wiki.yaml` — Workspace configuration, namespace prefixes, and `fmt` defaults.
- `wiki/` — Contains markdown files with semantic frontmatter.
  - `Person_Shape.md` — Validation shape for Person documents.
  - `Ethan_Davidson.md` — An example Person document.

## Commands

- **Check** (integrity: SHACL, route safety, layout frontmatter):
  ```bash
  wiki check
  ```
- **Lint** (conventions: broken links, filename pattern, heading style):
  ```bash
  wiki lint
  ```
- **Preview** (starts a local dev server with auto-reload):
  ```bash
  wiki serve --watch
  ```
- **Build** (compiles to static HTML site):
  ```bash
  wiki build
  ```
