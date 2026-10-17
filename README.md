# Shamrock Whiskers website

Static, mobile-friendly website ready for GitHub Pages. No build tools needed.

## Publish
1. Create a **public** GitHub repository (e.g. `shamrock-whiskers`).
2. Upload **the contents of this folder** (not the enclosing folder) to the repository's root, commit to `main`.
3. Repository **Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save**.
4. In Pages, set custom domain to `shamrockwhiskers.com`. The `CNAME` file is included.
5. At your domain registrar, configure apex A records for GitHub Pages: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`. For `www`, create CNAME to `YOUR_GITHUB_USERNAME.github.io` (replace placeholder). Remove conflicting A/AAAA/CNAME records for those hostnames.
6. Wait for DNS propagation, verify domain in GitHub if prompted, and enable **Enforce HTTPS** when available.

## Before promotion
- Replace the illustrated cat in `assets/cat-portrait.svg` with a licensed photograph if desired.
- Confirm show schedule, judges, entry URL and admission fees before publishing them.
- Update the TICA link to the actual show listing once confirmed.
- Add official Facebook URL and sponsor logos once supplied.
- Confirm whether the club should be described as a TICA affiliated club and use TICA logos only with permission.
- Current membership links open email; no personal data is collected by the website itself, and there is no payment processing.

## Edit
Edit text in `index.html`, colours in `styles.css`, and mobile menu in `script.js`. Commit changes; Pages republishes automatically.
