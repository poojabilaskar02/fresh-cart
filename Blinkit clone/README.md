# FreshCart

A responsive, Blinkit-inspired grocery shopping demo built with HTML, CSS, Bootstrap 5, and vanilla JavaScript.

## Run locally

Open `index.html` in a browser, or serve this folder with VS Code Live Server. The site uses no build step. Internet access is needed for Bootstrap, Bootstrap Icons, Google Fonts, and Unsplash images.

## Pages

- `index.html` — home, category browsing, and curated picks
- `products.html` — searchable, filterable, sortable product catalog
- `cart.html` — quantity controls and persistent basket
- `checkout.html` — validated demo delivery form and order confirmation

## Project structure

```text
css/style.css
js/products.js
js/app.js
js/catalog.js
js/cart.js
js/checkout.js
```

Basket contents are saved in browser LocalStorage under `freshcart-cart`. Checkout is a portfolio demo; it does not process payments or submit orders to a server.
