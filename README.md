# Peter Atandoh — Academic Website

A responsive, dependency-free academic portfolio designed for GitHub Pages.

## Publish with GitHub Pages

1. Create a GitHub repository and push these files to its `main` branch.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **GitHub Actions** as the source.
4. The workflow in `.github/workflows/pages.yml` will publish the site after the next push. Its URL will appear under **Settings → Pages** and in the workflow run summary.

For a personal site at `https://<username>.github.io`, name the repository `<username>.github.io`. A repository with another name publishes at `https://<username>.github.io/<repository>/`.

## Customize

- Edit content and links in `index.html`.
- Adjust colors, typography, and layout in `styles.css`.
- The small-screen navigation and automatic copyright year are in `script.js`.
- Replace the `PA` mark in `assets/favicon.svg` if you prefer another icon.

The Google Fonts link is optional; system fallbacks are included. All site functionality works without a build step or JavaScript framework.
