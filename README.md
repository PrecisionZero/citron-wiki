# Citron Wiki

Official player-facing documentation for **Citron**, a Fabric Minecraft modpack focused on performance, comfort, and carefully selected quality-of-life features.

**Wiki:** https://precisionzero.github.io/citron-wiki/

## Edit the wiki

The site uses [MkDocs Material](https://squidfunk.github.io/mkdocs-material/). Most changes only require editing Markdown files in `docs/`.

- `docs/` — all documentation pages.
- `mkdocs.yml` — navigation, theme, and site settings.
- `docs/assets/stylesheets/citron.css` — custom styling.
- `.github/workflows/pages.yml` — automated GitHub Pages build and deployment.
- `requirements.txt` — documentation dependencies.

## Preview locally

Install Python, then run:

```bash
python -m pip install -r requirements.txt
python -m mkdocs serve
```

MkDocs prints a local preview address in the terminal.

Check the site before pushing:

```bash
python -m mkdocs build --strict
```

## Deployment

Pushing changes to `main` triggers the GitHub Actions workflow. In the repository settings, GitHub Pages must use **GitHub Actions** as its build and deployment source.

See [the contribution guide](docs/contributing.md) for writing conventions.
