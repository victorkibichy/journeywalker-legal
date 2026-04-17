# My Journey Walker Legal Site

This folder contains a ready-to-host legal mini-site:

- `index.html` (Legal Center)
- `privacy.html` (Privacy Policy)
- `terms.html` (Terms of Service)
- `styles.css` (shared style)

The app currently links to:

- `https://journeywalker.app/privacy`
- `https://journeywalker.app/terms`

## Option A: Host on your main domain

Configure routes on your web host so:

- `/privacy` serves `privacy.html`
- `/terms` serves `terms.html`
- `/legal` or `/` serves `index.html`

## Option B: GitHub Pages quick deploy

1. Create a repository (or use an existing website repo).
2. Copy all files from this folder to the repository root.
3. Enable GitHub Pages from `Settings > Pages`.
4. Use branch deploy (for example, `main` root).
5. Your legal pages will be available at:
   - `https://<username>.github.io/<repo>/privacy.html`
   - `https://<username>.github.io/<repo>/terms.html`

If you use this option, update URLs in `ProfileView.swift` accordingly.

## Option C: Netlify/Vercel quick deploy

1. Create a new static site.
2. Upload this folder as the publish directory.
3. Add custom domain `journeywalker.app` (or subdomain like `legal.journeywalker.app`).
4. Configure redirects if needed so `/privacy` and `/terms` point to the corresponding files.

## Notes

- Review legal wording with counsel before production release.
- Keep effective/last updated dates current.
- If your data practices change, update both policy and app links immediately.
