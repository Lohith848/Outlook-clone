# Outlook clone (PWA)
Static app, no build step. Mail is stored only in the browser (localStorage).

## Deploy on Vercel
1. Push this folder to a GitHub repo (or run `npx vercel` inside it).
2. Import the repo in Vercel: Framework Preset = Other, no build command, output directory = `.`
3. Open the URL on your phone -> browser menu -> Install app / Add to Home Screen.

After changing files, bump `C='outlook-v1'` in sw.js so installed copies update.
