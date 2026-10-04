# Maruti Enterprise — GitHub Pages package

This package contains the built Maruti Enterprise website and a GitHub Actions workflow that publishes it to GitHub Pages.

## Publish it

1. Create a GitHub repository and upload the contents of this package, keeping the `.github` and `site` folders in place.
2. In the repository, open **Settings → Pages** and set the source to **GitHub Actions**.
3. Push the files to the `main` branch, or run **Deploy to GitHub Pages** from the repository's **Actions** tab.

The workflow publishes the static files in `site/`, so it works both at a repository URL such as `https://username.github.io/repository/` and at a custom domain.

The source website's canonical and social-preview metadata currently points to `https://marutihiring.com/`. If you host it at a different domain, update those URL values in `site/index.html`.

## Files

- `site/` — ready-to-serve website files, images, and assets.
- `.github/workflows/deploy-pages.yml` — automatically deploys the site to GitHub Pages.