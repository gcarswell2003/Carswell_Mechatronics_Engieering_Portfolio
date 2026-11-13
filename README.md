# Gabriel Carswell — Engineering Portfolio

A static portfolio published through GitHub Pages. The homepage is intentionally concise: a short introduction, the current Dodge senior design project, and a complete list of project case studies. Each project title opens its own breakdown page.

## Site structure

- `dist/index.html` — homepage and project index
- `dist/styles.css` — shared site styling
- `dist/projects/` — individual project pages
- `.github/workflows/pages.yml` — deploys the `dist` folder to GitHub Pages

## Updating a project

Edit the matching page under `dist/projects/`. Keep updates undated and organize them around project context, design decisions, progress, evidence, and next steps. Update the homepage project card if the summary or current milestone changes.

The Dodge project page includes a local GLB preview for SolidWorks exports. The selected model remains in the visitor's browser session and is not uploaded. To make a model viewable by everyone, add an approved `.glb` file to the repository and link it from the project page.

## Deploying

Push changes to `main`; the GitHub Actions workflow publishes `dist` to GitHub Pages.
