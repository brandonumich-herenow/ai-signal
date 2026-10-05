# AI SIGNAL

A small static weekly briefing site for Anocha.

## Files
- `index.html` — permanent interface
- `styles.css` — visual design
- `app.js` — loads current issue and archive
- `issues/index.json` — tells the site which issue is current
- `issues/YYYY-MM-DD.json` — one weekly issue

## GitHub Pages
1. Create a new public GitHub repository, e.g. `ai-signal`.
2. Add all files in this package to the repository root and push.
3. In GitHub: Settings → Pages.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Choose `main` and `/ (root)`, then Save.
6. GitHub will provide the permanent Pages URL.

## Weekly publishing model
A new issue only requires:
1. Add `issues/YYYY-MM-DD.json`.
2. Change `current` in `issues/index.json` to that filename.
3. Add the filename to `archive`.
4. Commit/push.

No database or server is required.
