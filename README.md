# aegisinfinity

Static site for **AEGIS INFINITY LLC** — security cameras, alarms, and digital signage.

## Stack
- Plain HTML + Tailwind CDN
- No build step, no analytics
- Mobile-first responsive
- IntersectionObserver reveal-on-scroll

## Files
- `index.html` — home
- `businesscard-g1/index.html` — Jeevan Singh contact card
- `businesscard-sid/index.html` — Sidharth Choudhary contact card
- `_headers` — long-cache for static assets (Render / Netlify-style)

## Local preview
```bash
python3 -m http.server 8000
```

## Deploy
Render static site → root, no build command, publish dir = `.`
