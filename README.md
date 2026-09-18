# Attenious

**Watch your child's focus grow.**

Landing page for Attenious — adaptive attention & focus games for kids ages 4–10, with weekly PDF progress reports for parents.

## Files

- `index.html` — the complete landing page (hero, interactive adaptive puzzle demo, features, sample report, waitlist form, FAQ)
- `robots.txt` — crawler rules
- `netlify.toml` — Netlify build config: fetches `logo.png` from the [v1.0.0 release asset](https://github.com/mohitjatktp/attenious/releases/tag/v1.0.0) at build time and publishes the repo as a static site

## Logo

The logo lives as a release asset (`logo.png` in v1.0.0), downloaded automatically during the Netlify build. To replace it: upload a new asset to a release and update the URL in `netlify.toml` — or simply commit a `logo.png` to the repo root and remove the `command` line from `netlify.toml`.

## Deploy

On Netlify: **Add new site → Import an existing project → GitHub → pick this repo** — no build settings needed (they come from `netlify.toml`).

## Notes

- The waitlist form currently shows a success message client-side; connect it to your email tool (or a Supabase table) when you launch.
- SEO/GEO: meta tags, Open Graph and JSON-LD (SoftwareApplication + FAQPage) are in `index.html`. Update the canonical URL and `og:image` once the final domain is known.
