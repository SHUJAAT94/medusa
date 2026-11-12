# Abdali Baba Supermarket — presentation demo

Responsive, dependency-free storefront concept for Abdali Baba Supermarket, Quetta. Uses the supplied logo and shop photograph hosted on Cloudinary. Product artwork is original inline SVG; products and PKR prices are illustrative.

## Run

From this directory, run `python3 -m http.server 8080`, then open http://localhost:8080. Alternatively open `index.html` directly in a browser.

For Vercel, select `demos/abdali-baba` as Root Directory, use Other as the framework, and leave Build Command empty. Publish only as a demonstration until the client approves it.

## Features

- Responsive homepage, categories, product search, sorting and product details.
- Basket quantity controls and browser-local basket persistence.
- Simulated checkout using fixed sample details; no personal information collected, no orders transmitted and no payments processed.
- Native accessible dialogs, keyboard controls and persistent demonstration notices.
- `noindex,nofollow` metadata for this client concept.

## Production boundary

This is a standalone presentation prototype inside the Medusa fork, not a running Medusa commerce application. It does not change Medusa packages or require their installation. After approval, create a dedicated Medusa application and storefront, then replace the sample catalogue/cart/checkout with server-backed Medusa APIs. Confirm actual catalogue, product photography, pricing, delivery rules, payment provider, stock process, customer privacy requirements, hosting and maintenance before launch. `noindex` is not access control; restrict hosting access if confidentiality is required.
