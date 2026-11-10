# Razin Iqbal Kabir — personal site

Live at https://razinkabir.com (GitHub Pages, served from `main`; razin-kabir.github.io and www.razinkabir.com redirect there). The domain is registered with Cloudflare, which also hosts its DNS.

## Files

- `index.html`: the whole site, with styles and script included. There's no build step.
- `CNAME`: tells GitHub Pages to serve the site at razinkabir.com. Don't delete it.
- `cv.pdf`: the public CV that the "Download CV" buttons serve. It has no street address, phone number or referees.

## How it's updated

The site follows the main CV in Google Drive (the newest `CV_Razin Iqbal Kabir_…` file in the CV folder). A daily scheduled task checks that file. When it changes, the task syncs the copy in Drive → Personal → razin-kabir-website, regenerates `cv.pdf`, updates the matching parts of `index.html` and pushes to `main`. GitHub Pages republishes a minute or two later.

Hand edits to `index.html` are fine too. Commit them here and they'll be kept.
