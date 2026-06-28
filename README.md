# Momentum PWA

This folder contains the installable PWA version of Momentum.

## Files

- `index.html` — the app
- `manifest.json` — Android/Chrome/Brave install metadata
- `service-worker.js` — offline caching
- `icons/` — app icons

## Important

A PWA must be opened from a web address using HTTPS, such as GitHub Pages, Netlify, Vercel, or Cloudflare Pages. It usually will not install properly when opened directly from Downloads as a local file.

## Install on Android with Brave or Chrome

1. Upload this folder to a static web host.
2. Open the hosted `index.html` URL on your Android phone.
3. Tap the browser menu `⋮`.
4. Choose `Install app` or `Add to Home screen`.
5. Name it `Momentum` and tap Add/Install.

After installation it should launch fullscreen, keep your data locally on the phone, and work offline after the first load.
