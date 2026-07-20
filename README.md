# Haofeng Ma — Academic Homepage

An English academic homepage built with [al-folio](https://github.com/alshedivat/al-folio) for research networking and graduate-study applications.

## Content

- Research interests and contact information: `_pages/about.md`
- Research projects: `_projects/`
- Web CV: `_data/cv.yml`
- Downloadable CV: generated from `_data/cv.yml` by RenderCV
- Public contact links: `_data/socials.yml`
- Future publications: `_bibliography/papers.bib`
- Future research notes: `_posts/`

## Updating the site

1. Edit the relevant Markdown, YAML, or BibTeX file.
2. Commit and push to the `main` branch.
3. GitHub Actions rebuilds and deploys the site automatically.

Avoid modifying theme internals unless necessary. Keeping personal content in the files above makes future al-folio upgrades substantially easier.

## Preview and deployment

Docker is **not required** to edit, publish, or maintain this site. The intended workflow is:

1. Edit content locally or in GitHub.
2. Push to the `main` branch.
3. GitHub Actions builds the site and publishes the `gh-pages` branch.
4. Review the deployed GitHub Pages URL.

A local Jekyll or Docker preview is optional.

## Deployment

The repository is currently private and GitHub Pages is intentionally disabled. The `Validate site` workflow builds the site and stores a private artifact for review.

When the homepage is ready to publish, make the repository public, set `url` in `_config.yml`, and restore a Pages deployment workflow. Do not enable Pages while the site is intended to remain private.
