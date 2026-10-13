# Candy Spark

Ukrainian product showcase for Candy Spark sweets, built with Astro and deployed to GitHub Pages.

## Local development

```sh
npm ci
npm run dev
```

## Production build

```sh
npm run build
npm run preview
```

The project is configured for the GitHub Pages path `/candy-spark/`.

## GitHub Pages

The workflow in `.github/workflows/deploy.yml` builds and deploys the site when changes reach `main`. In the repository settings, set **Pages → Build and deployment → Source** to **GitHub Actions**.
