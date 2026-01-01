# AbilityWave Solutions — Website (development)

This repository contains the source for a modular, static website for AbilityWave Solutions. The site lives in the `site/` folder and is intentionally simple and framework-agnostic.

Local preview

```bash
cd site
python3 -m http.server 8000
# open http://localhost:8000
```

Deployment

- Use GitHub Pages (either via `docs/` on `main` or a `gh-pages` branch), or add a GitHub Actions workflow to publish `site/` output. I can add a workflow if you want.

Repository structure

- `site/` — HTML pages and assets
- `site/assets/css` — styles
- `site/assets/js` — small client JS (nav + tag filtering)

Next steps

- Add real content, images, and blog posts (MD -> HTML pipeline if preferred).
- Add CI to lint HTML/CSS and deploy automatically.

# AbilityWaveSolutions — Main-Website

[![GitHub Actions - Deploy Pages](https://github.com/AbilityWaveSolutions/Main-Website/actions/workflows/deploy-pages.yml/badge.svg)](https://github.com/AbilityWaveSolutions/Main-Website/actions/workflows/deploy-pages.yml)

This repository contains the static website for Ability Wave Solutions.

## Contents
- `site/` — HTML pages, assets, and site-specific README

## Latest changes
- 2026-01-01: Committed all workspace changes and updated this README to summarize the update.

## Notes
- To stage and commit local changes:

```bash
git add -A
git commit -m "Commit all changes and update README"
git push origin main
```

For more details see the `site/` folder.


Readme file contents. 
