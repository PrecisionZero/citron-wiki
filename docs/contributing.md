# Contributing to the Wiki

The wiki is designed to be maintained with ordinary Markdown edits. Keep pages focused, link related information, and avoid duplicating long instructions.

## Where to edit

- `docs/` — user-facing pages.
- `mkdocs.yml` — navigation, theme, and Markdown extensions.
- `docs/assets/stylesheets/citron.css` — custom visual styling.
- `.github/workflows/pages.yml` — build and deployment automation.
- `requirements.txt` — Python documentation dependencies.

## Local preview

Install Python, then run:

```bash
python -m pip install -r requirements.txt
python -m mkdocs serve
```

MkDocs prints a local URL to open in your browser. It refreshes the preview as you edit files.

## Validate before publishing

```bash
python -m mkdocs build --strict
```

Fix warnings and errors before pushing. Check that every new page is linked in `mkdocs.yml` and that relative Markdown links point to the correct file.

## Writing rules

- Use short, descriptive headings.
- Put the action first in procedures.
- Prefer numbered steps for sequences and bullets for unordered options.
- Explain risks before destructive actions.
- Distinguish verified pack behavior from general Minecraft advice.
- Do not invent download URLs, compatibility promises, performance claims, or release dates.
- Keep version-specific details labelled as such.
