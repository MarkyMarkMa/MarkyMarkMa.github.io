# Haofeng Ma — Academic Homepage

Haofeng Ma’s bilingual academic homepage. The site uses the MIT-licensed [Hugo Coder](https://github.com/luizdepra/hugo-coder) theme and is published with GitHub Pages.

## Content maintenance

- Home identity and social links: `hugo.toml`
- English content: `content/en/`
- Chinese content: `content/zh/`
- Language and color controls: `layouts/_partials/float.html`
- English CV data: `_data/cv.yml`
- Downloadable CV: `static/cv/Haofeng_Ma_CV.pdf`
- Visual customization: `assets/css/custom.css`
- Avatar placeholder: `static/images/avatar.svg`

## Deployment

The `Deploy Hugo site to GitHub Pages` workflow builds and publishes the site on every push to `main`. In the repository settings, set **Pages → Source** to **GitHub Actions** once before the first deployment.

## Theme license

Hugo Coder is distributed under the MIT License. Its source and license are retained in the `themes/hugo-coder` submodule.
