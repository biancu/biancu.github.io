# Bogdan Iancu — academic homepage

A single-file, zero-build personal researcher page (`index.html`). No frameworks,
no dependencies — it runs anywhere static files are served. Fonts load from Google
Fonts; everything else is inline. Dark and light themes follow the visitor's system
setting.

## Deploying to GitHub Pages

This is a standalone site. Published from a repository named after your GitHub
account, it serves from your root domain.

### Root user site (recommended) → `https://biancu.github.io`

1. Create a new **public** repository named exactly `biancu.github.io`.
2. Push the contents of this folder (`index.html`, `.nojekyll`, `README.md`) to `main`.
3. In the repo's **Settings → Pages**, set **Source = Deploy from a branch**,
   **Branch = `main` / `/ (root)`**.
4. The site goes live at `https://biancu.github.io` within a minute or two.

### Custom domain (optional)

Add a `CNAME` file containing your domain (e.g. `bogdaniancu.com`) and configure the
DNS records shown in **Settings → Pages**.

## Editing

Everything is in `index.html`:

- **Content** lives in plain, labelled sections (`About`, `Research`, `Experience`, …).
- **Colours, fonts, spacing** are CSS custom properties in the `:root` block at the top.
- To add a **photo**, drop an image in this folder and reference it from the hero.

## Notes

- All employment and grant entries use **years only**; no funding amounts are shown.
- The publication list is summarised — ORCID is linked as the authoritative source.
- Contact email on the page: `bogdan.iancu@novia.fi`.
