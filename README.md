# Safe Gardens, Safe Cats — Complete Website

A six-page, mobile-friendly static website, based on the team's 2026 presentation and draft manuscript. Designed for GitHub Pages; no build tools or backend needed.

## Website files
- `index.html` — home page
- `plants.html` — searchable 15-entry plant guide
- `research.html` — study methodology, survey and SD-CPRI limitations
- `book.html` — book information and draft publication status
- `events.html` — planned December 5, 2026 library presentation and outreach
- `about.html` — student team, milestones, acknowledgments
- `css/style.css` — responsive styling
- `js/site.js` — mobile menu and footer year
- `js/plants.js` — search/filter and expandable plant cards
- `js/data.js` — data for browsers opening local HTML files directly
- `data/plants.json` — editable canonical plant profiles
- `images/plants/` — student project plant photographs, when available
- `images/project/` — field and veterinarian interview photographs

## Preview
Open `index.html` in your browser. Works with `file://` because the plant data are also included in `js/data.js`.

## Publishing on GitHub Pages
Keep all files and folders at the root of your existing repository. **Do not delete your `.git` folder.** Copy the extracted contents into your working repository folder, replacing matching files. In Git Bash run:

```bash
git status
git add .
git commit -m "Add research, book and events pages"
git push origin main
```

GitHub → repository Settings → Pages → Deploy from branch `main` and `/ (root)`.

## Editing plant information
Edit `data/plants.json`, then keep `js/data.js` synchronized. It contains the same array with `window.SGSC_PLANTS = ` before it and a semicolon after it. Without updating both, browser cards won't reflect your edits.

## Important publication checks
1. Have a veterinarian verify the plant safety advice. This website is educational, not a diagnosis or treatment tool.
2. Obtain permissions for student and interview photographs before publicly distributing. The photos for true lilies and azalea are intentionally omitted pending verified licensing.
3. Confirm final author/contributor names and photograph credits.
4. Confirm the planned December 5 library event with the venue before public promotion.
5. Survey counts (114 respondents) are not representative of all San Diego cat owners. SD-CPRI is exploratory and unvalidated.
6. Do not upload confidential survey information or personal emails to this public repository.

This package replaces a previous **three-page** version; the new `research.html`, `book.html`, and `events.html` are fully implemented and linked from sitewide navigation.
