# Velnaris Group

Marketing site for **Velnaris Group LLC**, a staffing company at 18 Congress Cir W, Roselle, IL 60172.

Static site, no build step: `index.html` + `logo.svg`. Trilingual (EN / ES / 中文) via the `T` dictionary at the bottom of `index.html`.

## Edit before launch
In `index.html`, the `SITE` object near the top of the `<script>`:
- `email` — the inbox that receives requests (currently a placeholder)
- `phone` — leave empty to hide the phone row

The contact form opens the visitor's email app (`mailto:`); hook it to a form backend later if needed.

## Preview locally
```
npx serve .
```

## Deploy
Any static host works (Cloudflare Pages, Netlify, Vercel, GitHub Pages, Railway static). Point the publish directory at the repo root.
