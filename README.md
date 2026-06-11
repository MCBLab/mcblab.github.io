# MCB Lab website

This repository contains the Quarto website for the Marques-Coelho Bioinformatics Lab.

## Local preview

```bash
quarto preview
```

## Render

```bash
quarto render
```

The site source is at the repository root. Content from the previous `_tmp` site has been migrated into the `people/` and `research/` sections.

Pushes to `main` are rendered and deployed by the GitHub Pages workflow in `.github/workflows/publish.yml`. The repository's Pages source must be set to **GitHub Actions**.
