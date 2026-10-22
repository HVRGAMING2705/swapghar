# SwapGhar — Home Exchange for India

**Swap homes. Skip the hotel bill.**

SwapGhar is a home-exchange web app for India: verified travellers swap homes instead of paying for hotels. A points system makes non-simultaneous swaps work — host guests to earn points, spend points to stay anywhere.

## What is inside

- Explore homes: 12 seed listings across Mumbai, Goa, Bengaluru, Hyderabad, Delhi, Jaipur, Kochi and Pune, each with a verified host, points-per-night and amenities.
- Two exchange modes: Points swap (spend points from your wallet) and Simultaneous swap (offer one of your own listed homes).
- My Trips, List your home, Favourites, Trust & safety (ID verification, Rs 10 lakh home-protection cover), Membership (Free vs Plus Rs 4,999/year, display-only in this demo).

All state persists in the browser via localStorage (key swapghar_v1). Points and prices are illustrative.

## Tech

Zero-build static site: a single self-contained index.html (inline CSS + JS, no external CDNs or images), plus vercel.json security headers, robots.txt and sitemap.xml.