# Deploy (GitHub Pages)

This repo is intended to be served via **GitHub Pages** from the `/docs` folder.

## Current public pages
- `/` (index): `docs/index.html`
- `/iso27001-toolkit/`: `docs/iso27001-toolkit/index.html`
- `/iso-27001-statement-of-applicability-template/`: `docs/iso-27001-statement-of-applicability-template/index.html`
- `/iso-27001-risk-register-template/`: `docs/iso-27001-risk-register-template/index.html`
- `/nis2/`: `docs/nis2/index.html`

## Publish steps
1) Commit changes in this repo
2) Push to GitHub
3) GitHub repo Settings → Pages → Deploy from branch → set `/docs`

## Post-publish checklist
- Verify the 3 ISO pages load and the “Get the Toolkit” CTA opens Stripe checkout
- Verify UTM params are preserved on CTA buttons
