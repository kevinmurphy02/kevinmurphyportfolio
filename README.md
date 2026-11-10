# Kevin Murphy | Portfolio v4

Version 3 with two new case studies and matching project previews. Static HTML and CSS, ready for the existing GitHub Pages project path. No build step.

## New projects

- `projects/good-driver.html`: Good Driver Incentive Program. Team-based Django/MySQL rewards platform; public hosted application link only. No private GitHub repository link or proprietary code included.
- `projects/chair-configurator.html`: 3D Product Configurator. React/TypeScript/React Three Fiber portfolio app, linked to its public GitHub repository. No invented live demo URL.
- `assets/good-driver-preview.svg` and `assets/chair-preview.svg`: Clearly labeled conceptual artwork, **not real application screenshots**.

The homepage has seven project cards. The two new cards include an optional **Technical overview** disclosure plus a direct link to their full case study, consistent with the rest of the website.

## Deploy

Extract the archive, then replace the files at the published root of `github.com/kevinmurphy02/kevinmurphyportfolio` with this folder's `index.html`, `styles.css`, `projects/`, and `assets/`. Keep those folder names and relative paths.

Site: https://kevinmurphy02.github.io/kevinmurphyportfolio/

This package does not deploy itself.

## Verification and caveats

- The public hosted application https://team06.cpsc4911.com/ exposes the Team #06 application and login. Dashboards may require credentials.
- The public repository https://github.com/kevinmurphy02/atelier-3d-modeling-chair-configurator contains project details and Vite setup instructions. At review time, it did not list a verified live demo.
- Driver app page describes the **team's project**, not verified individual ownership of features. Add your own contribution section once you choose precise contributions.
- Chair pricing is illustrative, client-side. No sales transactions or backend are claimed.
- The package contains no screenshots of either app. You can add real screenshots later by replacing the SVG previews and changing `img src` in the relevant HTML files.
- Footer email CSS was corrected to stay on one line at common desktop and phone sizes.

## Files

- `index.html`
- `styles.css`
- `projects/*.html`: Seven long-form case studies
- `assets/`: illustrations, diagrams and TigerMed attachments

## Local checks

All relative local references were checked against the packaged files. A headless browser navigation attempt was blocked by this execution environment, so cross-browser visual rendering was not verified.
