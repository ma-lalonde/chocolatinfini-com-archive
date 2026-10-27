# Chocolat Infini archive

Static copy of the chocolatinfini.com home, store and about pages, in English (`/`) and French (`/fr/`).

- `site/` holds the published pages and their assets. Links are relative, so the site works at any base path.
- `npm run dev` serves `site/` at http://localhost:4321/ (Node only, no dependencies).
- `.github/workflows/deploy.yml` publishes `site/` to GitHub Pages on every push to `main`. In the repository settings, set Pages > Source to "GitHub Actions".
