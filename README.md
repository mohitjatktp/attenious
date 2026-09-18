# Attenious

**Watch your child's focus grow.**

Landing page for Attenious — adaptive attention & focus games for kids ages 4–10, with weekly PDF progress reports for parents.

## Files

- `index.html` — the complete landing page (hero, interactive adaptive puzzle demo, features, sample report, waitlist form, FAQ)
- `logo.png` — the Attenious logo
- `robots.txt` — crawler rules

## Deploy

Any static host works. On Netlify: **Add new site → Import an existing project → GitHub → pick this repo** — no build settings needed.

## Notes

- The waitlist form currently shows a success message client-side; connect it to your email tool (or a Supabase table) when you launch.
- SEO/GEO: meta tags, Open Graph and JSON-LD (SoftwareApplication + FAQPage) are in `index.html`. Update the canonical URL and `og:image` once the final domain is known.
