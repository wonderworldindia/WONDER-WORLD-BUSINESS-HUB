# VANSH CUISINE 360 — V3

Customer-facing restaurant menu and WhatsApp order enquiry PWA.

## Included
- 27 menu categories and 181 transcribed menu entries from the supplied 16-page PDF.
- Search, category filtering, sorting and cart quantity controls.
- Cart and customer checkout draft saved locally on the device.
- WhatsApp order and party/function enquiry preparation for 9368576489.
- Online/offline status indicator and Service Worker cache for offline reopening after first successful online visit.
- Five color themes; introductory home-page Hindi/English toggle.
- UPI payment deliberately reserved for a future update; no payment is collected.

## Run locally
Service Workers require HTTPS or localhost. From this folder run:

```bash
python -m http.server 8000
```

Open `http://localhost:8000` in Chrome. Visit once while online, then test offline using browser DevTools > Network > Offline. For Android installation, deploy to HTTPS (GitHub Pages is suitable), open the site in Chrome and use Install App / Add to Home screen when offered.

## GitHub Pages
Upload the contents of this folder to a repository (or a subfolder), then enable Settings > Pages > Deploy from a branch > main > root (or select the correct subfolder if supported by your deployment workflow). Keep all paths and folders unchanged.

## Important limitations
- WhatsApp is an external service and requires internet to send the order. Offline mode preserves the menu/cart/draft but cannot deliver an order until connectivity returns.
- WhatsApp opening is not restaurant acceptance. Restaurant must confirm availability, final amount and order acceptance.
- MRP items are excluded from the numeric subtotal until actual MRP is confirmed.
- A few Burger line-wrap ambiguities in the printed menu are flagged for owner verification; do not treat those lines as verified prices.
- The language switch translates the main introductory text only; the full menu and checkout labels remain in English in this build.
- No UPI/payment gateway is enabled.