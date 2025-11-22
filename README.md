# twigfire.github.io — splash page

This repository serves a simple splash page for twigfire.com showcasing Zach Liscio's Drafting and Residential Construction Design services.

Included files:
- `index.html` — the splash page (contains your name, blurb, and email).
- `styles.css` — lightweight styles used by the page.
- `logo.png` — your uploaded logo; referenced from the root of the repo.
- `CNAME` — tells GitHub Pages to use `twigfire.com` as the custom domain.

Quick setup steps
1. Files were pushed to the `main` branch in this commit. GitHub Pages will serve the site automatically when the branch exists and Pages is configured.

2. DNS configuration for your domain (`twigfire.com`):
   - For the apex (twigfire.com): add A records pointing to GitHub Pages IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - (Optional) Add a CNAME for `www` pointing to `twigfire.github.io` if you want `www.twigfire.com` to work.

3. Wait for DNS propagation (can take minutes to a few hours), then in the Pages settings enable "Enforce HTTPS" once the certificate is issued.

If you'd like any changes (use a subfolder for the logo, switch to SVG, tweak copy or styling), tell me and I will update the files.