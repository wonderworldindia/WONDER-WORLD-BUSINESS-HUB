# VANSH CUISINE 360 — V2 Preview

A separate premium V2 customer-facing restaurant app.

## Included in this branch
- Main page, responsive stylesheet and app logic
- Digital menu data (27 categories / 181 menu entries)
- WhatsApp order request and party/function enquiry flows
- PWA manifest and service worker
- SVG app icons in `assets/icons/`
- Audit report

## Image assets
The three WebP images (hero pizza, Indian thali, restaurant interior) have been generated and packaged separately as `VANSH-CUISINE-360-V2-IMAGE-ASSETS.zip`. They still need to be added to `assets/images/` in this repository. Until then, the homepage photo slots will not render.

## Deployment status
Not ready for public deployment yet. Add the three WebP files, then verify the GitHub Pages preview and test on a real Android device.

## Limitations
- Hindi toggle currently changes the homepage introduction/tagline only.
- No online payment gateway is included.
- WhatsApp order and party booking are requests only; restaurant confirmation is required.
- Generated food/restaurant imagery is illustrative, not verified photography of the actual premises or dishes.
- Some source menu entries are flagged for owner verification.

The original V1 and `main` branch are not modified.


Deployment note: V2 is published as a separate folder on the main GitHub Pages branch. Local WebP photography is still pending; the feature cards use safe visual placeholders until those assets are added.
