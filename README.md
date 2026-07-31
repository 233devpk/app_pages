# BubbleDock GitHub Pages

Static Privacy Policy + Support pages for the BubbleDock Play Store listing.

## Files

| File | Play Console field |
|------|--------------------|
| `privacy.html` | **App content → Privacy policy** URL |
| `support.html` | **Store listing → Support URL** (and contact page) |
| `index.html` | Optional hub |
| `styles.css` | Shared design |

## Before you push

1. Replace every `YOUR_EMAIL@gmail.com` with your real support email (same as Play Console).
2. Optional: remove the yellow “replace email” helper notes in the HTML if you want a cleaner public page.

## Publish on GitHub Pages

1. Create a new public GitHub repo (e.g. `bubbledock-pages`).
2. Upload **all files in this folder** to the **root** of the repo (or to a `docs/` folder).
3. Repo → **Settings → Pages**:
   - Source: **Deploy from a branch**
   - Branch: `main` (or `master`)
   - Folder: `/ (root)` — or `/docs` if you put files there
4. Wait 1–2 minutes, then open:

- `https://YOUR_USERNAME.github.io/bubbledock-pages/privacy.html`
- `https://YOUR_USERNAME.github.io/bubbledock-pages/support.html`

5. Paste those URLs into Google Play Console for BubbleDock.

## User-site shortcut (optional)

If you create a repo named `YOUR_USERNAME.github.io` and put these files at its root, URLs become:

- `https://YOUR_USERNAME.github.io/privacy.html`
- `https://YOUR_USERNAME.github.io/support.html`
