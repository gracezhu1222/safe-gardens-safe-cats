# Safe Gardens, Safe Cats · Static website

A three-page static website based on the uploaded 2026 student book manuscript and research presentation.

## Contents
- `index.html`: homepage, book status, research, and proposed December 5 event
- `plants.html`: searchable 15-entry plant guide with expandable summaries
- `about.html`: methods, survey results, project team, and acknowledgments
- `css/style.css`: responsive styling
- `js/site.js`, `js/data.js`, `js/plants.js`: navigation, plant data, interactive search/filter
- `data/plants.json`: machine-readable editable plant data
- `assets/images/`: selected original project photographs from the manuscript

## Preview
Open `index.html` in any browser. No build step required. Alternatively, from this folder run `python -m http.server 8000` then visit `http://localhost:8000`.

## Publish
Create a GitHub repository, upload this folder's contents to the root of the `main` branch, then open Settings → Pages → Deploy from a branch → `main` and `/ (root)`.

## Required before public release
1. Have a veterinarian confirm every plant profile and emergency guidance. This site reproduces an unvalidated student project guide, not a clinical product.
2. Verify photos and obtain any needed permission for student field photography and photos showing people. Images marked pending were omitted because manuscript image credits/licenses remain unresolved.
3. Confirm final book author/contributor credits with the team.
4. Confirm venue permission and event time before advertising the proposed December 5, 2026 workshop.
5. If you need a contact address, create a project-specific shared inbox; do not publish students' personal email addresses.
6. Review privacy and consent before posting survey microdata or identifiable images. The website currently displays only aggregate survey counts.
7. Replace or remove placeholder book display once the final book is approved for distribution.

## Source details
Source: *Safe Gardens, Safe Cats*, student manuscript (41 pages), and the uploaded community research presentation. Data includes all 15 original entries, including rosemary as a clearly identified non-toxic comparison. Survey counts are from 114 nonrandom respondents; these do not establish San Diego-wide rates. The SD-CPRI concept was not validated or used to compute an official ranking.
