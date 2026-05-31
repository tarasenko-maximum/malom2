# MALOM INVEST — A Living Document

Editorial landing page for **MALOM INVEST**, featuring the flagship **TATARHILL** estate on the Fruška Gora slopes.

A static, single-page site built as a 7-chapter "living document" in a heritage-editorial style (EB Garamond + IBM Plex Mono, bone/parchment/terracotta palette).

## Stack
- Static HTML + [Tailwind CSS](https://tailwindcss.com/) (CDN)
- Vanilla JS (scroll reveal, custom cursor, mobile menu, ticker)
- Brand logos as inline SVG (MALOM mark, TATARHILL monogram)

## Structure
```
index.html              # the whole site
assets/
  images/               # photography (home, Fruška Gora, world map)
  img/                  # brand logo SVGs (malom-mark, tatarhill-mark)
```

## Local preview
Any static server works, e.g.:
```bash
npx serve .
# or
python -m http.server 4321
```

## Deployment
Hosted on [Vercel](https://vercel.com/). Pushing to the `main` branch triggers an automatic production deployment.
