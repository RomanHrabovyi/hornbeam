# Hornbeam — Klaviyo email marketing

One-page site for Hornbeam (Roman Hrabovyi): UA/EN, light/dark theme, single self-contained `index.html`.

## Before going live
Open `index.html`, find `const CONFIG` near the bottom and fill in:
- `FORM_ENDPOINT` — Formspree form URL (e.g. `https://formspree.io/f/xxxxxx`)
- `CALENDLY_URL` — your Calendly event link

## Hosting
GitHub Pages: Settings → Pages → Deploy from branch → `main` / root.
Or Netlify / Cloudflare Pages: connect this repo, no build command, publish directory `/`.
