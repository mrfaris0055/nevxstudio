# NevX Studio Website

A mobile-first website for NevX Studio, built with plain HTML, CSS, and JavaScript. There is no npm install or build step.

## Preview

Open `index.html` in a web browser. Keep the folders together so the styles, scripts, and images load correctly.

## Pages

- `index.html` — home and featured services
- `shop.html` — service catalog and category filters
- `product.html?id=1` — details for a service (change the number to view another item)
- `cart.html` — cart, quantity controls, and WhatsApp order message
- `about.html` — studio details and process
- `contact.html` — inquiry and consultation request forms

## Edit services

Edit the `NEVX_PRODUCTS` array in `js/products.js`. Each service has a unique numeric `id`, name, category, description, features, image path, and price. Use `null` for a custom quote. Contact settings are in `NEVX_CONFIG` near the bottom of the same file.


## Publish as a static website

Upload this folder's contents to a GitHub repository. A static host such as Netlify can publish the repository root with no build command. See `PROJECT_BRIEF.md` for launch notes and placeholders that need real business details.

The included UPI QR is a labelled placeholder, and consultation requests are sent through WhatsApp. This static website does not process payments or provide secure shared admin access.
