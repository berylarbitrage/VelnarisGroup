# Velnaris Group

Marketing site for **Velnaris Group LLC**, an industrial staffing company serving Illinois, Texas, Georgia and New York.

Static site, no build step: `index.html` + `logo.svg`. Trilingual (EN / ES / 中文) via the `T` dictionary at the bottom of `index.html`.

## Settings
In `index.html`, the `SITE` object near the top of the `<script>`:
- `phone` — shown in the top bar, contact section and footer; the contact form opens a text message to this number.

## Deploy
Served by GitHub Pages from `main` (root): https://berylarbitrage.github.io/VelnarisGroup/
Any push to `main` redeploys automatically.
