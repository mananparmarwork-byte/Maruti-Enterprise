# Maruti Enterprise website

Static site, ready for GitHub Pages. Live address once published:
https://mananparmarwork-byte.github.io/Maruti-Enterprise/

## Upload to GitHub

1. Create a new **public** repository named exactly `Maruti-Enterprise` (capital M and E).
2. Unzip this archive and upload **everything inside the folder** to the repository root,
   including the hidden `.github` folder and `.nojekyll`. (Do not upload the ZIP itself.)
   - Easiest: GitHub Desktop, or `git add . && git commit -m "Publish site" && git push origin main`.
   - Do not use drag-and-drop in the browser: it skips hidden folders like `.github`.
3. In the repo go to **Settings -> Pages -> Build and deployment -> Source: GitHub Actions**.
4. Open the **Actions** tab, wait for "Publish website to GitHub Pages" to turn green (1-2 min).

## Using a different repository name or a custom domain

Paths are set for `/Maruti-Enterprise/`. If you rename the repo, replace `/Maruti-Enterprise`
with `/<new-name>` in every `.html` file and in `assets/index-*.js`
(also the `base:"/Maruti-Enterprise"` setting inside that JS file).
For a root domain (e.g. marutienterprise.org), replace `/Maruti-Enterprise` with an empty string
and set `base:""`.
