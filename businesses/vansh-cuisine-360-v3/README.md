# VANSH CUISINE 360 — V3 Customer App

A separate V3 customer-facing copy. V1, V2 and the repository homepage are preserved.

## Included
- Digital menu, customer cart, WhatsApp order request and party enquiry
- Original menu data: 27 categories / 181 entries, carried forward without price edits
- Responsive design, five themes, PWA manifest and SVG assets
- Hindi/English switch for key navigation, labels and home introduction
- V3-only service-worker cache namespace; cleanup cannot delete other Wonder World app caches
- Startup resilience, invalid cart cleanup and event date validation

## Customer policy
WhatsApp submission is a request, not restaurant acceptance. Availability, final bill, delivery charges, taxes and MRP items require restaurant confirmation. No payment gateway is included. Food/interior SVGs are illustrative, not verified restaurant photography.

## Testing required after publication
Check GitHub Pages URL, installability, first-load and repeat-load offline behavior, Android Chrome, WhatsApp handoff and cache isolation on a real device. Static source checks do not prove device behavior.
