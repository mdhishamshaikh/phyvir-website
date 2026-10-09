# PHYVIR website

Quarto website for the PHYVIR project, published with GitHub Pages.

## Edit locally (RStudio)

1. Open this folder in RStudio (File > New Project > Existing Directory).
2. Edit any `.qmd` file; the Team page reads `team.csv`.
3. Click **Render** on a `.qmd` file, or run `quarto::quarto_preview()` for a live preview.

## Publish on GitHub

1. Create a repository (e.g. `phyvir-website`) and push this folder to `main`.
2. On GitHub: **Settings > Pages > Build and deployment > Source: GitHub Actions**.
3. Replace `YOUR-GITHUB-USER` in `_quarto.yml` with your account or organisation name.
4. Every push to `main` now renders and publishes the site automatically.

The site will appear at `https://YOUR-GITHUB-USER.github.io/phyvir-website/`.
