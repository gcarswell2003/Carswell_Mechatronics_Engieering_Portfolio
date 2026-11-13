# Gabriel Carswell Engineering Portfolio

A buildless, responsive portfolio site. The deployable page lives at `dist/index.html`.

## Updating the portfolio

Project summaries, roles, stages, milestone labels, and design-process entries are kept together in the `projects` array near the bottom of `dist/index.html`. Edit those fields to update the site. Entries marked `add details` are prompts for information to fill in; remove or replace those prompts before calling the portfolio complete.

## SolidWorks model previews

The Dodge project includes a browser-based `.GLB` preview using Google's `<model-viewer>` component. The current control previews a locally selected file in the current browser session; it does not upload or retain it. To publish a model, add an approved, optimized GLB under `dist/models/` and reference that asset in the page. A GLB is for viewing and sharing, not an editable native SOLIDWORKS assembly.

SOLIDWORKS supports GLB and glTF import/export. For a single-file browser asset, use GLB.

## GitHub Pages

The included GitHub Actions workflow publishes `dist/` whenever code is pushed to `main`, or when the workflow is run manually. In the repository's **Settings → Pages**, set the build source to **GitHub Actions** if it is not already selected.

Anything committed to this repository and published through GitHub Pages should be treated as public. Do not add confidential employer material, credentials, or files that you do not intend to share publicly.
