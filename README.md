# LLM Manual

**Understanding LLMs · The Complete Course** — a static site served via [GitHub Pages](https://pages.github.com/).

**Live site:** https://arvicco.github.io/llm-manual/

## Layout

The site is served from the repository root (GitHub Pages source = `main` branch, `/` root):

- `index.html` — course table of contents
- `*.html` — chapters
- `style.css` — styles
- `img/` — figures
- `.nojekyll` — serve files as-is, skip Jekyll

## Local preview

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```
