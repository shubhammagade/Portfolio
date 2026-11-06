# Shubham Magade — SAP CPI Portfolio

Single-page portfolio (one `index.html`, no build step). Works on GitHub Pages or Vercel.

## Files
- `index.html` — the whole site
- `Shubham_CV.pdf` — used by the "Get my resume" / "Download resume" buttons
- `shubham.jpg` — your photo in the About section (to change it, replace this file with another 4:5 portrait of the same name)

## Publish on Vercel (same as Sandip's site, free)
1. Put these files in a GitHub repository.
2. Sign in at https://vercel.com with GitHub, click **Add New → Project**, pick the repository and click **Deploy** (no settings needed).
3. Rename the project to `shubhammagade` in Settings to get `shubhammagade.vercel.app`.

## Or publish on GitHub Pages
1. Create a public repository named `YOUR-USERNAME.github.io`.
2. Upload the files to the root.
3. Settings → Pages → Deploy from a branch → `main` / root → Save.

## Editing projects
Projects are in the `P` array inside the `<script>` at the bottom of `index.html`. The cards, filters, case-study popups and the Ctrl K search all update from it.

## Before publishing
- Client names are intentionally left out; projects are described by industry only.
- The contact form opens the visitor's email app addressed to you; nothing is stored.
