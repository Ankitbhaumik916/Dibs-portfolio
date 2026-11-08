# Dibyabrata Bhattacharya — Portfolio

Single-page portfolio: a WebGL hero (glass "hello", streak background, dot-dissolve, pointer fluid), an about section, and an interactive "offline" power-button footer.

- `index.html` — the whole site (HTML, CSS, JS; fonts embedded as base64)
- `assets/` — portrait and resume PDF
- `vercel.json` — caching and security headers

No build step. External runtime dependencies load from CDNs: three.js 0.170.0 and Lenis 1.1.13 (jsDelivr), footer clip and poster (CloudFront).

## Run locally

Open `index.html` directly, or serve the folder:

```sh
npx serve .
```

## Deploy

Import the repo in Vercel with the **Other** framework preset, no build command and output directory `.` (the defaults).
