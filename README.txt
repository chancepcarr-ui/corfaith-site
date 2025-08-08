# CORfaith Static Site

Ready-to-deploy files for GitHub Pages.

## Files
- `index.html` — single-page site (Tailwind CDN)
- `assets/corfaith-cloud-gold.svg` — gold open cloud logo
- `favicon.png` — site icon

## Quick Deploy (GitHub Pages)
1. Create a new repo named `corfaith-site` (public).
2. Upload all files in this folder (including `assets` and `favicon.png`).
3. In **Settings → Pages**, set:
   - Source: **Deploy from a branch**
   - Branch: **main** / root (`/`)
4. (Optional) Add a `CNAME` file containing `corfaith.com` for your custom domain.
5. In Namecheap DNS, point:
   - `A` records for `@` to GitHub Pages IPs: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `CNAME` for `www` → `<your-username>.github.io`
6. Wait for DNS to propagate, then visit `https://corfaith.com`.

(*MX/DKIM records for Zoho Mail should remain unchanged.*)
