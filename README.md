# DiA Residential — Static Website

Single-page React application built with inline JSX (Babel standalone). No build step required.

## Deploy

Drop these files into any static host (GitHub Pages, Netlify, Vercel, Cloudflare Pages, S3, etc.):

```
index.html
styles.css
data.js
ui.jsx
pages.jsx
app.jsx
tweaks-app.jsx
tweaks-panel.jsx
assets/
```

### GitHub Pages

Website is live at ` https://hoda834.github.io/dia-website/`.

## Local Preview

Open `index.html` directly in a browser, **or** serve the folder with any static server:

```
npx serve .
# or
python3 -m http.server 8000
```

## Editing

- **Copy & content** → `data.js`
- **Page sections** → `pages.jsx`
- **Shared UI (nav, footer, buttons)** → `ui.jsx`
- **Theme + style** → `styles.css`
- **Images** → drop into `assets/`

## Tech

- React 18 (UMD) + Babel Standalone — no bundler
- Plain CSS with custom properties
- Hash-based routing (no server config needed)
- Tap-to-call buttons (`tel:` links), email (`mailto:`) links
- Light/dark theme toggle, persists per-browser
