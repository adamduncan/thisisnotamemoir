# This Is Not a Memoir

Minimal static single-page site: HTML, CSS, and optional JS. No build step.

## Stack

- **HTML** — Modern meta tags (Open Graph, Twitter Card), responsive viewport, favicon links
- **CSS** — One file, CSS variables, logical properties, `prefers-color-scheme` dark mode
- **JS** — ES module (`script.js`), loaded with `type="module"`

## Structure

```
├── assets/
│   ├── favicon.ico
│   ├── icon.svg
│   └── apple-touch-icon.png
├── index.html
├── styles.css
├── script.js
├── netlify.toml
└── README.md
```

## Local development

Open `index.html` in a browser, or serve the directory:

```bash
npx serve .
```

## Deploy (Netlify)

- Connect this repo in Netlify. Build command: none. Publish directory: `.`
- Config is in `netlify.toml`; deploys run on push to the default branch.

## Assets to add

- **Favicons:** Place `favicon.ico` (32×32), `icon.svg`, and `apple-touch-icon.png` (180×180) in `assets/`. Placeholder empty files are there; replace with real icons. See [Evil Martians favicon guide](https://evilmartians.com/chronicles/how-to-favicon-in-2021-six-files-that-fit-most-needs).
- **Social preview:** Update `og:url`, `og:image`, and Twitter meta in `index.html`; add a 1200×630 image (e.g. `og-image.png`) when ready.

## License

MIT
