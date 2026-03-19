# Deployment & Email Capture — NIS2 Landing Page

This doc explains **exactly** how to publish `site/nis2/index.html` and connect an email capture form.

## Option A (fastest): Carrd

### A1) Create the page
1. Create a new Carrd site (Blank).
2. Add 1 **Embed** element (type: “Code”).
3. Paste the contents of `site/nis2/index.html` into the Embed.
   - If Carrd strips `<head>`/CSS, instead paste only the `<body>` content and move the CSS into Carrd’s Settings → Site → “Custom CSS”.

### A2) Email capture
You have two implementation paths:

#### Path 1: Use provider’s embed form
- Replace the disabled input/button block inside the `#checklist` card with the HTML embed code from ConvertKit/Beehiiv/Mailchimp.

#### Path 2: Simple link CTA (no embed)
- Replace the button with a link to a hosted form (e.g., Beehiiv subscribe page, ConvertKit landing page).

### A3) Delivery
- Configure an automation to send the checklist content (or a link) upon signup.
  - For now the checklist lives at `offers/nis2/lead-magnet-checklist.md`.


## Option B: Netlify Drop (no accounts needed if done manually)
1. Create a folder containing only `index.html`.
2. Drag-and-drop to https://app.netlify.com/drop
3. (Later) add a custom domain.


## Option C: Cloudflare Pages / GitHub Pages
1. Put `site/nis2/index.html` at repo root as `index.html`.
2. Enable Pages from the repo.
3. (Later) add custom domain + HTTPS.


## Email capture provider notes
### ConvertKit
- Use a Form embed (inline) and set the incentive email to deliver the checklist.

### Beehiiv
- Use the subscribe embed or link to the hosted subscribe page.

### Mailchimp
- Use embedded signup form HTML.


## Tracking (optional but recommended)
- Add Plausible/GA4 script in `<head>`.
- Add UTM parameters to the CTA links.
