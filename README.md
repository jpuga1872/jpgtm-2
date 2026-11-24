# JP GTM website

Static site, no build step.

- `index.html` — English
- `es/index.html` — Spanish
- `assets/portrait.jpg` — portrait
- `favicon.*`, `apple-touch-icon.png`, `icon-*.png` — icons

## Deploy on Vercel

1. Push this folder's contents to the root of a GitHub repository.
2. In Vercel, choose Add New > Project and import the repository.
3. Framework preset: Other. Leave build command and output directory empty.
4. Deploy. The Spanish version is served at `/es/`.
