# Edit the Wiki

The wiki is written in Markdown and built with MkDocs Material. Most edits only require changing a file in `docs/`.

## Where things live

| Path | Purpose |
|---|---|
| `docs/` | Wiki pages |
| `mkdocs.yml` | Navigation and site settings |
| `docs/assets/stylesheets/citron.css` | Orange theme |
| `requirements.txt` | Build dependencies |
| `.github/workflows/pages.yml` | Automatic deployment |

## Preview changes

Install Python, then run:

```bash
python -m pip install -r requirements.txt
python -m mkdocs serve
```

Open the local address printed in the terminal. The preview updates as you edit.

## Check before publishing

```bash
python -m mkdocs build --strict
```

Fix any errors before pushing your changes to `main`. GitHub Actions will build and deploy the site.

## Page structure

Use this simple pattern for most pages:

1. **Short introduction** — what the page covers.
2. **Main information** — steps, settings, or a short table.
3. **Related pages** — links grouped at the bottom.

Keep paragraphs short. Use numbered lists for steps, bullets for options, and tables only when comparing values. Link to related pages in a dedicated section rather than scattering navigation links through the text.

## Writing style

- Explain the task directly.
- Include extra detail only when it helps someone complete the task or avoid a mistake.
- Do not promise performance gains or compatibility that has not been tested.
- Keep version-specific details clear.
