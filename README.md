# Razin Iqbal Kabir — personal site

A single static page (`index.html`) with no build step. Put it on any static host.

## Files

- `index.html` — the whole site (styles and script included)
- `cv.pdf` — public copy of the CV (no street address, phone number or referees). The "Download CV" buttons link to it. To update, export a new public version and upload it with the same name.

## Publish on GitHub Pages (free)

1. Sign up at github.com. Your username becomes your address, yours is `razin-kabir`, so the site will be `https://razin-kabir.github.io`.
2. Create a new **public** repository named exactly `razin-kabir.github.io`.
3. In the repository, choose **Add file → Upload files**, drag in `index.html` and `cv.pdf`, then **Commit changes**.
4. Go to **Settings → Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**, and save.
5. Wait a minute or two, then open `https://razin-kabir.github.io`.

To update the site later, upload the new `index.html` (or edit it in the browser with the pencil icon) and commit. It republishes on its own.

## Optional: your own domain

A `.com` such as `razinkabir.com` costs about US$10–11 a year at at-cost registrars like Cloudflare or Porkbun. A `.ca` is restricted by CIRA's Canadian Presence Requirements: individuals must be Canadian citizens or permanent residents, so a work permit alone doesn't qualify.

To connect a domain: in **Settings → Pages → Custom domain**, enter it, add the DNS records GitHub shows you at your registrar, then tick **Enforce HTTPS**. The site stays hosted free on GitHub Pages; the domain is just the address.
