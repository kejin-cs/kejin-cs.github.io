# Ke Jin Academic Homepage

Personal academic homepage built with [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io).

Website: <https://kejin-cs.github.io/>

## Editing

- `_config.yml`: personal profile, contact links, site metadata, and URL.
- `_pages/about.md`: biography, research focus, projects, author lists, honors, education, and contact details.
- `_data/navigation.yml`: navigation links and section anchors.
- Project media remain in the repository root under their original filenames. Images keep their aspect ratios; `UAV.gif` loops automatically.

The site uses AcadHomepage's original layouts, styles, and responsive paper-box components. The default template avatar is a placeholder. No manuscript PDF, manuscript title, publication claim, unconfirmed dates, GPA, Google Scholar identifier, or CV link is included.

## Publishing

GitHub Pages builds Jekyll from the `main` branch and `/ (root)`. Do not add `.nojekyll` or a separate root `index.html`; the homepage is generated from `_pages/about.md`.

The `Validate Jekyll` workflow builds and checks the site without deploying it. Its artifact can be downloaded for a local preview. The Google Scholar crawler and analytics are disabled until real configuration is supplied.

## Template and license

Forked from [RayeRen/acad-homepage.github.io](https://github.com/RayeRen/acad-homepage.github.io). The upstream MIT license and copyright notice are retained in `LICENSE`. Original setup instructions are preserved in `docs/UPSTREAM-README.md` and `docs/README-zh.md`.

AcadHomepage incorporates Font Awesome and is influenced by Minimal Mistakes and Academic Pages; their upstream acknowledgments and licensing notices are retained.
