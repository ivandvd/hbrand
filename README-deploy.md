# Hyperwood Brand Guidelines — static site (edition 1.1)

This folder is the complete website. It has no build step and no server code: upload it anywhere that serves static files.

## What is in it

- `index.html` — the whole guidelines site (single page, sidebar navigation, motion library)
- `assets/` — logos, graphics, templates, platform exports, fonts, tokens, the PDF guide
- `Hyperwood-Brand-Kit-v1.1.zip` — the full kit, including the editable PowerPoint guide (the "Download brand kit" button links to it)
- `site.webmanifest` — web app manifest (icons, theme color)

## Hosting

- **GitHub Pages** (this repo): Settings → Pages → Source "Deploy from a branch" → `main` / `/ (root)`. The repo must be public on a free plan.
- **Netlify**: drag this folder onto app.netlify.com/drop. **Vercel**: `npx vercel` in this folder (preset "Other"). **Cloudflare Pages**: direct upload.
- Custom domain: add a `CNAME` file containing the domain (for GitHub Pages) or set it in the host's dashboard, then update the two `og:` URLs at the top of `index.html`.

## Before going live

- Replace bracketed placeholders in the page copy (`[domain]`, `[handle]`, `[Brand contact]`, `[Email]`, `[Channel]`).
- Items tagged **Draft** or **To confirm** on the site need sign-off (mission, value propositions, product facts).
- Fonts are self-hosted from `assets/fonts/` (Manrope and IBM Plex Mono, OFL licensed); nothing loads from third parties.
- Downloads are plain links. Ambient surfaces use WebGL with a 2D fallback and freeze when the visitor prefers reduced motion.

## Editing

The site is one HTML file. Search for a section id (for example `id="color-palette"`) to find a page. Colors, type, spacing and motion values live in the `:root` block at the top of the first `<style>` tag.
