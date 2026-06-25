# Limbic — marketing site

A single self-contained `index.html` (all CSS/JS inline) for the Limbic landing
page. No backend, no build step, no secrets.

Published automatically to GitHub Pages by `.github/workflows/deploy.yml` on
every push to `main`. The source of truth lives in the `agent-emotion-system`
repo at `web/index.html`, which syncs here via CI.
