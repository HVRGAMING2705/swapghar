# SwapGhar — Home Exchange for India

**Swap homes. Skip the hotel bill.**

SwapGhar is a home-exchange web app for India: verified travellers swap homes
instead of paying for hotels. A points system makes non-simultaneous swaps work —
host guests to earn points, spend points to stay anywhere.

## What's inside

- **Explore homes** — 12 seed listings across Mumbai, Goa, Bengaluru, Hyderabad,
  Delhi, Jaipur, Kochi and Pune, each with a flat inline-SVG illustration tinted
  per city (no external images), a verified host, points-per-night and amenities.
- **Search & filter** — by city/locality text search plus popular-city chips.
- **Listing detail** — host verification card (Govt ID, phone, member since),
  house rules, and a live points calculator.
- **Two exchange modes**
  - *Points swap* — spend points from your wallet (seed balance: 1,000 pts).
  - *Simultaneous swap* — offer one of your own listed homes in exchange.
- **My Trips** — every request you send, with status chips.
- **List your home** — a form that publishes your home to the grid instantly and
  makes it available to offer in simultaneous swaps.
- **Favourites** — heart any card; saved across visits.
- **Trust & safety** — ID verification, ₹10 lakh home-protection cover,
  verified-only reviews, secure in-app messaging.
- **Membership** — Free vs SwapGhar Plus (₹4,999/year), display-only in this demo.

All state (points, listings, favourites, trips) persists in the browser via
`localStorage` under the key `swapghar_v1`. Points and prices are illustrative.

## Tech

Zero-build static site: a single self-contained `index.html` (inline CSS + JS,
no external CDNs or images), plus `vercel.json` security headers, `robots.txt`
and `sitemap.xml`. Deploy by dropping the folder on any static host (Vercel,
Netlify, GitHub Pages).

## Run locally

```sh
cd swapghar
python3 -m http.server 8000
# open http://localhost:8000
```
