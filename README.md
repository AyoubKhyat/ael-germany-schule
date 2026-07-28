# AEL Germany Schule — Institut Allemand Marrakech

Website for AEL Germany Schule, a German language institute in Marrakech, Morocco. Built as a Progressive Web App with multi-language support and rich motion design.

## Features

- **Progressive Web App** — installable, offline-capable via service worker
- **Multi-language** — internationalization via i18n
- **3D CSS styling** — depth and motion effects
- **GSAP animations** — scroll-driven and interactive
- **Responsive** — mobile-first design
- **SEO-ready** — semantic HTML, meta tags, manifest

## Tech stack

- **Structure:** Vanilla HTML5
- **Styling:** CSS3 (with 3D transforms)
- **Interactions:** Vanilla JavaScript
- **Animation:** GSAP
- **i18n:** JavaScript i18n library
- **PWA:** Service Worker + Web App Manifest

## Project structure

```
ael-germany-schule/
├── index.html
├── styles.css / styles-3d.css
├── script.js
├── gsap-animations.js
├── sw.js               # service worker
├── manifest.json       # PWA manifest
└── assets/             # images, fonts, media
```

## Getting started

Serve the folder with any static server:

```bash
# using Python
python -m http.server 8000

# or using Node
npx serve .
```

Open http://localhost:8000

## About

Built by [Ayoub Khyat](https://github.com/AyoubKhyat) — full-stack developer, Marrakech.

For custom multilingual sites, PWAs, or educational platforms, contact via [Ibda3 Digital](https://ibda3-digital.vercel.app/) or [Fiverr](https://www.fiverr.com/ayoubkhyat).
