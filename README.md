# mormaid.github.io

Security notes from The Deep.

This is a custom Jekyll site for GitHub Pages - theme to be customised.

## How it works

- `_config.yml` stores site-wide settings.
- `_layouts/` contains page wrappers.
- `_includes/` contains reusable chunks like the header and footer.
- `_posts/` contains blog posts.
- `assets/css/style.scss` controls the styling.
- `.github/workflows/pages.yml` builds and deploys the site with GitHub Actions.

## Deployment

When changes are pushed to `main`, GitHub Actions builds the Jekyll site and deploys it to GitHub Pages.