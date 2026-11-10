# Kevin Murphy | Portfolio v3

A static, editorial portfolio designed for GitHub Pages. No build step, npm dependencies, framework or JavaScript required.

## Structure

- `index.html`: Home page and project index
- `projects/*.html`: Five standalone, long-form case studies
- `styles.css`: Global type, layout, spacing and responsive styling
- `assets/*.svg`: Custom, conceptual illustrations
- `assets/tigermed-architecture.png`: Actual diagram extracted from the user's presentation
- `assets/TigerMed_Cloud_Architecture_Portfolio.pdf` / `.pptx`: Original academic presentation

## Design direction

Alegreya and Alegreya Sans (requested through Google Fonts, with local serif/sans fallback). Warm paper background, dark type, muted brick accent, large margins, fewer boxes, no neon, no résumé-style filler slogans. Strongly editorial rather than a startup landing page.

## Deployment

1. Download / extract the zip.
2. Open `index.html` locally to inspect (some browsers may restrict local file navigation, but links work when served).
3. In `github.com/kevinmurphy02/kevinmurphyportfolio`, replace the published root files with this folder's contents. Preserve the `projects/` and `assets/` directories.
4. GitHub Pages will continue serving `https://kevinmurphy02.github.io/kevinmurphyportfolio/` after the deployment completes.

The CSS and every link are relative so this works under the `/kevinmurphyportfolio/` repository path. The site has **not** been published; deployment requires your action.

## Link audit

- https://github.com/kevinmurphy02/College_Basketball_Training_Model
- https://github.com/kevinmurphy02/College_Basketball_Prediction_Model
- https://github.com/kevinmurphy02/SQL_BLS_Cleanup
- https://github.com/kevinmurphy02/ai_safety_policy_RAG

## Content notes

- The first four projects were checked against their public repositories and the current portfolio.
- TigerMed content is grounded in the user-provided PPTX, PDF and standalone case study.
- TigerMed is carefully labeled a proposal, not a deployment, and the cost is expressly labeled a classroom estimate.
- The diagram and graphics are only illustrations; the site does not claim a live deployment or fabricated results.
- The internship title/employer is intentionally not asserted because the supplied resume variants disagree.
- An unfinalized résumé PDF is not embedded. Add a verified PDF to `assets/` and link it in navigation if desired.
- Email and LinkedIn match user-provided résumé materials. Update them directly in the HTML if needed.
