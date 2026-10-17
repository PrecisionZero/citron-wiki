# Citron Wiki

The documentation site for Citron.

## Repository layout

Keep content in two places:

- `assets/` — CSS, images, logos, and other static files.
- `pages/` — every page published to the wiki.

The root files are only for configuration and deployment.

```text
assets/
  citron.css
pages/
  index.md
  getting-started/
  versions/
  features/
  help/
  _templates/
mkdocs.yml
requirements.txt
.github/workflows/pages.yml
README.md
```

## Edit pages

Pages are Markdown files. Most pages use this structure:

1. A short introduction, if needed.
2. The main information.
3. Related pages at the bottom, when useful.

Avoid putting navigation links in the middle of paragraphs.

### Add a feature

1. Copy `pages/_templates/feature.md` to `pages/features/<feature-name>.md`.
2. Add the page to the Features section in `mkdocs.yml`.
3. Add it to `pages/features/index.md`.
4. Link it from each relevant version page and name the mod that provides it.

### Add a subversion

1. Copy `pages/_templates/version.md` into the relevant major-version folder.
2. Name the file after the subversion.
3. Add it to the major-version index and `mkdocs.yml`.
4. List that subversion's features, linking each feature page and naming its mod.

Keep version lists newest first.

## Preview locally

Install Python, then copy the assets into the page source folder before running MkDocs.

**Windows PowerShell:**

```powershell
if (Test-Path pages/assets) { Remove-Item pages/assets -Recurse -Force }
Copy-Item assets pages/assets -Recurse
python -m pip install -r requirements.txt
python -m mkdocs serve
```

**macOS / Linux:**

```bash
rm -rf pages/assets
cp -R assets pages/assets
python -m pip install -r requirements.txt
python -m mkdocs serve
```

Run `python -m mkdocs build --strict` to check the site before pushing. GitHub Actions deploys changes pushed to `main`.
