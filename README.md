# Sprout UI — Preview Site

Interactive preview and showcase for [Sprout UI](https://github.com/akhildesai20/Sprout-UI) — a lightweight, sustainable, zero-dependency UI library.

## What's in here

- **index.html** — Full single-page showcase
- **style.css** — Preview page styles (uses Sprout tokens)
- **script.js** — Live performance audit + copy buttons + nav toggle

## Features

- 🌱 **Live performance audit** — real browser metrics: transfer size, DOM nodes, JS heap, CSS rules, CO₂ estimate
- 🧩 **16 component demos** — wired with actual Sprout CSS/JS via CDN
- ⚡ **Install section** — CDN, npm, and download tabs with copy buttons
- 📱 **Fully responsive** — works on mobile, tablet, desktop
- 🌗 **Theme toggle** — dark / light / high-contrast / auto

## Deploy to GitHub Pages

1. Create a new repo (e.g. `sprout-ui-preview`)
2. Push these three files to `main`
3. Go to **Settings → Pages → Source: main branch / root**
4. Your page will be live at `https://yourusername.github.io/sprout-ui-preview/`

## Sprout UI loads via CDN

```html
<link rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/@akhildesai20/sprout-ui@latest/dist/sprout.min.css" />
<script defer
  src="https://cdn.jsdelivr.net/npm/@akhildesai20/sprout-ui@latest/dist/sprout.min.js"></script>
```

No build step. No bundler. Just open `index.html`.

---

MIT License · [Sprout UI Docs](https://akhildesai20.github.io/Sprout-UI/) · [npm](https://www.npmjs.com/package/@akhildesai20/sprout-ui)
