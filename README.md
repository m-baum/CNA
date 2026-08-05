# Coincidence Analysis (CNA) — website

The worldwide community hub for Coincidence Analysis, a configurational
comparative method of causal inference.

Built with [Quarto](https://quarto.org). The rendered site is deployed to
GitHub Pages by a GitHub Actions workflow (`quarto-dev/quarto-actions`).

- Live site: https://cna-method.com
- Method & software: see the cna R package.

## Develop

```bash
cd site
quarto render      # build into _site/
quarto preview     # local preview
```

Push to `main` → the workflow renders and publishes to GitHub Pages
automatically.
