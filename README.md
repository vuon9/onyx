# ONYX — Curated Horology

![ONYX Homepage](screenshots/homepage-thumb.png)

> Full-page screenshots of all pages available in [`screenshots/`](screenshots/)

A luxury watch showcase website featuring 12 iconic timepieces from 9 legendary maisons.

## Pages

| Page | File | Highlights |
|------|------|------------|
| **Collection** | [`index.html`](index.html) | Aurora gold hero + typewriter headline + 12 watches with filter/search & detail modals |
| **Maisons** | [`brands.html`](brands.html) | 9 brand directory with rich modals (history, models, milestones) |
| **About** | [`about.html`](about.html) | Story, values, timeline, stats |
| **Journey** | [`journey.html`](journey.html) | Articles and insights |
| **Contact** | [`contact.html`](contact.html) | Contact form + info cards + consultation hours |

## Design

- Dark obsidian + gold theme
- Playfair Display + Inter fonts
- Unique hero effects per page (aurora canvas, sweep line, typewriter, shimmer, pulse)
- Responsive layout
- Real watch photography from Wikimedia Commons

## Serve

```bash
cd onyx && python3 -m http.server 8080 --bind 0.0.0.0
```

Visit `http://localhost:8080`
