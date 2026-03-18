# Deploy options — ISO 27001 Toolkit mini site

This site is a single static file: `index.html`.

## Option A (fastest, no repo): Cloudflare Pages (upload)
1. Cloudflare Dashboard → **Pages** → Create project
2. Choose **Upload assets**
3. Upload the contents of this folder:
   - `index.html`
4. Deploy → copy the public URL

## Option B (repo-based): GitHub Pages
1. Create a repo (public or private)
2. Put `index.html` at the repo root (or `/docs`)
3. GitHub Settings → Pages → Deploy from branch
4. Copy the public URL

## Option C (CLI): Netlify Drop (drag & drop)
1. Open https://app.netlify.com/drop
2. Drag this folder (or just `index.html`)
3. Copy the public URL

## Sanity checks after deploy
- CTA button opens the Google Form in a new tab
- Mobile view: hero + buttons readable
- Meta title/description look okay when shared

## Next distribution actions (once live)
- Post on LinkedIn and X using `../promo-assets-v1.md`
- Do 20 outbound emails using the template
