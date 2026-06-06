# A11yScanFix Documentation (MkDocs Material)

Source for the docs site at **https://docs.a11yscanfix.com**.

One site covers both Free and Pro. Pro-only pages and items are marked
with a **PRO** badge / admonition.

## One-time setup

You need Python 3.8+.

```bash
pip install -r requirements.txt
```

## Write and preview

Edit the Markdown files under `docs/`. Live preview with hot reload:

```bash
mkdocs serve
```

Open http://127.0.0.1:8000 - it reloads as you save.

## Build for your server

```bash
mkdocs build
```

This creates a `site/` folder containing a plain static website (HTML, CSS,
JS, search index). Upload the **contents of `site/`** to the web root of
`docs.a11yscanfix.com` (e.g. via FileZilla).

DNS: point `docs.a11yscanfix.com` at the same server, document root = where
you uploaded `site/`.

## Brand assets

Drop these into `docs/assets/images/` so the theme matches a11yscanfix.com:

- `logo.svg` (the eye badge, used top-left)
- `favicon.ico`

Copy them from the website project (`assets/images/`). Until they exist the
theme falls back to the Material default logo.

## Notes

- Brand colours (navy `#05386E`, green `#2FBE8B`) and fonts (DM Sans + Space
  Mono) are set in `docs/stylesheets/extra.css` and `mkdocs.yml`.
- No em-dash anywhere - plain hyphen only (house rule).
