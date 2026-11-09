# goldcrunch.my

Official website for **Gold Crunch Enterprise** — _Rich In Every Bite_.

> Status: 🚧 **Under development.** The live homepage currently shows a
> "Something Big Is Coming" placeholder banner.

## About

Gold Crunch Enterprise
Ground Floor, Lot 8996 (SL 11), Demak Square, Jalan Demak,
Petra Jaya, 93050 Kuching, Sarawak.

## Project structure

```
.
├── index.html              # Coming-soon homepage
└── assets/
    ├── css/
    │   └── style.css       # Styling (responsive, brand palette)
    └── images/
        ├── banner.webp     # Placeholder banner (primary, WebP)
        └── banner.jpg      # Placeholder banner (fallback, JPG)
```

## Run locally

It is a static site — open `index.html` directly, or serve it:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Deploy

Any static host works (GitHub Pages, Netlify, Vercel, Cloudflare Pages).
Point the `goldcrunch.my` domain at the host once a provider is chosen.

## Roadmap

- [x] Placeholder "Coming Soon" homepage
- [ ] Brand / product pages
- [ ] Product catalogue (Cornflakes Madu Gajus, Nutty Mix, …)
- [ ] Contact & store locator
- [ ] Online ordering
