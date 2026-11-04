# Colnor — women’s suit store prototype

A standalone storefront prototype for Colnor’s women’s suit collection. It was developed in a separate `Sumissura-Inspired` folder and does not modify the Clad and Shine storefront in `Project Recreate`.

## Preview

Open `index.html` for the landing page or `collection.html` for the suit collection. For local navigation and browser storage, run a static server from this folder, for example:

```powershell
py -m http.server 8010
```

Then open `http://127.0.0.1:8010/`.

## Included

- Colnor branding, women’s suits navigation, full-viewport hero carousel, categories, product catalog, sticky shopping bar, and responsive layout.
- A 35-item sample catalog priced in KSh 6,500–12,000, with product detail pages, galleries, color swatches, sizes XS–XXL, and quantities.
- Local shopping bag, checkout preview with card/M-Pesa choices, and browser-local demo order records.
- About, contact, and demo order lookup pages, plus working footer destinations.
- Suit campaign images downloaded to `assets/` for offline rendering. See `assets/SOURCES.txt` for source URLs and rights status. Most product-card imagery currently uses these sample suit photos; replace them with licensed, product-specific Colnor photography before launch.

Contact form submissions, orders, and the bag are saved only in this browser. Email delivery, inventory, order fulfillment, card processing, and M-Pesa are not connected.
