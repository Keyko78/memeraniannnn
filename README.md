# May & Kevin — Wedding Invitation

Static bilingual (English / Thai) wedding site. No build step.

## Publish on GitHub Pages
1. Create a new repository and upload everything in this folder (`index.html`, `images/`, `.nojekyll`).
2. Repo **Settings → Pages → Build and deployment → Source: Deploy from a branch**, branch `main`, folder `/ (root)`.
3. After a minute your site is live at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

## Add / replace / delete photos
Put your pictures in the `images/` folder with these exact names (`.jpg`, `.jpeg`, `.png` or `.webp`):

| File name | Where it appears |
|---|---|
| `v1` | Hotel exterior / entrance |
| `v2` | Hotel interior / ballroom |
| `g1` … `g6` | "A Little Glimpse of Us" gallery |

- **Upload / replace:** on GitHub open `images/` → *Add file → Upload files* (same name replaces it).
- **Delete:** delete the file in GitHub; the placeholder returns.
- Tip: resize photos to about 1600 px wide (under 500 KB) so the site loads fast.

## Edit text and details
Open `index.html` and edit the block marked `// ===== EDIT HERE =====` (Google Maps links, schedule, captions). Thai text lives in the `TH` and `THS` objects further down.
