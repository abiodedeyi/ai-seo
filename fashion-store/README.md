# Aurelle — Fashion Store Website

A complete, self-contained fashion store website. No frameworks, no build step,
no dependencies — just open `index.html` in any browser.

## What's included

- **Homepage** with hero banner, sticky navigation, and announcement bar
- **Collections** — shop by Women / Men / Accessories
- **Product grid** — 8 sample products with category filters and sale badges
- **Shopping cart** — slide-out drawer with quantities, totals, and
  localStorage persistence (the cart survives page refreshes)
- **Newsletter signup** section
- Fully **responsive** — works on phones, tablets, and desktops

## Run it locally

Just open the file:

```
open fashion-store/index.html
```

Or serve it:

```
cd fashion-store && python3 -m http.server 8000
# then visit http://localhost:8000
```

## Put it online (free options)

- **GitHub Pages** — repo Settings → Pages → deploy from branch, folder `/fashion-store`
- **Netlify / Vercel** — drag-and-drop the `fashion-store` folder, done in ~1 minute

## Make it yours

- **Brand name**: search for "Aurelle" in `index.html` and replace it
- **Products**: edit the `PRODUCTS` array near the bottom of `index.html` —
  name, category, price, sale price, colors
- **Images**: products currently use built-in illustrations; swap the `art()`
  function output for `<img src="...">` tags when you have real product photos
- **Colors/fonts**: tweak the CSS variables in `:root` at the top of the file

## Taking real payments

The checkout button is a demo. To sell for real, the simplest paths are:

1. **Stripe Payment Links** — create a link per product, point the buttons at them (no code)
2. **Snipcart** — add one script tag and HTML attributes to get a full cart + checkout
3. **Shopify Buy Button** — embed Shopify products into this site
