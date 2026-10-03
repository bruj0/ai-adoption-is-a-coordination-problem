# AI Adoption Is a Coordination Problem

Source for the public essay hosted at
<https://bruj0.github.io/ai-adoption-is-a-coordination-problem>.

- [`docs/index.md`](docs/index.md) is the canonical markdown source.
- The site is built with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/)
  and the [`mkdocs-panzoom-plugin`](https://github.com/lichtwellicht/mkdocs-panzoom-plugin)
  via `.github/workflows/docs.yml`, which deploys to GitHub Pages on every
  push to `main`.

## Build locally

```bash
uv sync --extra docs
uv run mkdocs serve
```

Open <http://127.0.0.1:8000>.
