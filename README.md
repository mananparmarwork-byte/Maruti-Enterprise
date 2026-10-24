# Maruti Enterprise — GitHub Pages export

This archive contains the built, static website and a GitHub Actions workflow for publishing it with GitHub Pages. It includes the homepage, service pages, images, CSS/JavaScript, SEO metadata, sitemap, and robots file.

## Upload and publish

1. Create a GitHub repository for the website.
2. Extract this archive and copy **all contents** (including `.github` and `.nojekyll`) into the repository root. Do not upload only the ZIP file.
3. Commit and push the files to the repository's `main` branch. GitHub Desktop is an easy way to upload the extracted folder.
4. In the repository, open **Settings → Pages** and set the source to **GitHub Actions**. The included workflow publishes the site after each push to `main`.

## Domain note

This build retains the site's configured canonical URLs and sitemap for `https://marutienterprise.org/`. It is intended to be served at the root of that domain. If you control the domain, add it under **Settings → Pages → Custom domain** and configure the DNS records GitHub shows there.

A default GitHub project address such as `username.github.io/repository-name/` uses a subpath; this export's root-based asset paths are not configured for that subpath. If you want to use that address instead of a custom domain, rebuild with the repository name as the base path.
