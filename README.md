# LLM Manual

**Understanding LLMs · The Complete Course** — a static site served via [GitHub Pages](https://pages.github.com/).

**Live site:** https://arvicco.github.io/llm-manual/

## Layout

The published site lives in [`docs/`](docs/) (GitHub Pages source = `main` branch, `/docs` folder):

- `docs/index.html` — course table of contents
- `docs/*.html` — chapters
- `docs/style.css` — styles
- `docs/img/` — figures
- `docs/.nojekyll` — serve files as-is, skip Jekyll

## Local preview

```sh
cd docs && python3 -m http.server 8000
# then open http://localhost:8000
```
