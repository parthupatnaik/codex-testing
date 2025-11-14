# Shiva Trilogy GitHub Pages Site

This repository hosts a single-page tribute site for Amish Tripathi's **Shiva Trilogy**, designed for deployment on GitHub Pages.

## Preview

The site features:

- A cinematic hero section introducing the trilogy.
- A timeline that outlines the publication journey of each book.
- Detailed spotlights for all three novels.
- A thematic grid that highlights recurring ideas from the saga.

## Local development

Open `index.html` in your browser to preview the page locally. All assets are loaded via CDN, so no build step is required.

## Deploying to GitHub Pages

This repository now includes a GitHub Actions workflow that publishes the static site to the `gh-pages` branch and updates the public Pages environment for you.

1. Push the repository (including the `.github/workflows/deploy.yml` file) to the `main` branch on GitHub.
2. Visit **Settings → Pages** and ensure that **Source** is set to **GitHub Actions**. (This only needs to be done once.)
3. Every push to `main` will trigger the workflow and automatically deploy the latest site.

As soon as the workflow finishes, GitHub exposes the live URL from the deployment summary, so you never have to publish the site manually again.

## Share a direct link

Once the GitHub Actions deployment completes, copy the URL from the workflow summary or use the canonical GitHub Pages format:

```
https://<your-github-username>.github.io/<this-repository-name>/
```

Replace `<your-github-username>` with the owner of the repository and `<this-repository-name>` with its exact name (capitalization matters). Anyone with this link can view the site without needing GitHub access.

Enjoy exploring the legend of the Neelkanth!


Deployment trigger update
