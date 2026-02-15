# This Is Not a Memoir

Minimal static single-page site: HTML, CSS, and optional JS. No build step.

## Stack

- **HTML** — Modern meta tags (Open Graph, Twitter Card), responsive viewport, favicon links
- **CSS** — One file, CSS variables, logical properties, `prefers-color-scheme` dark mode
- **JS** — ES module (`script.js`), loaded with `type="module"`

## Local development

Open `index.html` in a browser, or serve the directory:

```bash
npx serve .
```

## Deploy (Netlify)

- Connect this repo in Netlify. Build command: none. Publish directory: `.`
- Config is in `netlify.toml`; deploys run on push to the default branch.

## License

MIT
