# Ashley Morgan — Revenue Operations & AI Analytics Portfolio

A single-page interactive portfolio for **Ashley Morgan**, Director of Revenue & Sales Operations. Built as one self-contained HTML file with no build step — open `index.html` directly or serve any way you like.

## What's inside

- **Hero** with animated KPI counters
- **Scroll-scrubbed career timeline** — six roles, each with its own D3-driven mini visualization
- **Four featured projects** — ICP scoring, AE activity scorecard, executive forecasting (with live recompute sliders), and territory & annual planning — each with an inline interactive prototype
- **Filterable skill matrix** across six discipline areas
- **Contact** section

## Stack

Vanilla HTML, CSS, and JavaScript. The following libraries load from a CDN at runtime:

- [D3 v7](https://d3js.org/) — data viz
- [GSAP](https://gsap.com/) + ScrollTrigger — scroll-driven animation
- [Lenis](https://github.com/studio-freight/lenis) — smooth scroll
- [Fraunces](https://fonts.google.com/specimen/Fraunces) + [Quicksand](https://fonts.google.com/specimen/Quicksand) + [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts

No build step. No package manager. No framework.

## Run locally

Open `index.html` in a browser, or serve over HTTP:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Accessibility

- `prefers-reduced-motion` is respected — animations are skipped for users who request it.
- Keyboard focus states preserved.
- Color contrast tuned against WCAG AA on body text.

## Data

All prototype data is illustrative and generated client-side with a seeded PRNG so it is stable across reloads.

---

© 2026 Ashley Morgan. All rights reserved. Published as a portfolio piece — not licensed for reuse.
