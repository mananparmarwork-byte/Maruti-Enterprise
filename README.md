# Maruti Enterprise website

Built static website, ready to publish on GitHub Pages. Everything is at the repository root.

## Publish

1. Replace the repository contents with all files from this package (index.html, assets, images, .nojekyll, .github, ...).
2. Repository **Settings -> Pages -> Source: GitHub Actions**.
3. Push to `main` (or `master`), or run **Actions -> Deploy to GitHub Pages -> Run workflow**.

### If the `.github` folder will not upload
Skip the workflow: set **Settings -> Pages -> Source: Deploy from a branch -> main / (root)**.
The site files are already at the root, so this works without any workflow file.

## Note
`index.html` canonical and social-preview URLs point to `https://marutihiring.com/`. Change them if you host on a different domain.
