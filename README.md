# Citron Wiki

Documentation for **Citron**, a Fabric Minecraft modpack focused on performance and useful quality-of-life features.

**Website:** https://precisionzero.github.io/citron-wiki/

## Editing pages

Most content is in `docs/` as Markdown.

- `docs/` — wiki pages
- `mkdocs.yml` — navigation and site settings
- `docs/assets/stylesheets/citron.css` — orange theme
- `.github/workflows/pages.yml` — GitHub Pages deployment
- `requirements.txt` — build dependencies

## Preview locally

```bash
python -m pip install -r requirements.txt
python -m mkdocs serve
```

To check the build:

```bash
python -m mkdocs build --strict
```

Pushing to `main` triggers the deployment workflow. GitHub Pages should be configured to use **GitHub Actions**.

See [Edit the Wiki](docs/contributing.md) for the page structure and writing style.
