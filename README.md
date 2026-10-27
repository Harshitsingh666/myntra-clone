# Fashion Edit — Myntra-inspired storefront

A small educational fashion storefront built with plain HTML, CSS, and JavaScript. It recreates common online-shopping patterns such as category browsing, product search, sorting, a wishlist, and a shopping bag without a framework or build step.

> This is an independent learning project. It is not affiliated with or endorsed by Myntra. The catalog uses sample product data and remote Unsplash photos; it does not sell real products.

## Run it

Open `index.html` in a browser, or use VS Code Live Server. No dependencies or build tools are required.

## Features

- Responsive desktop and mobile storefront layout
- Category navigation, live product search, and price/rating sorting
- Wishlist and shopping bag saved in browser `localStorage`
- Bag drawer with quantity, item removal, and total calculation
- Accessible labels and lazy-loaded product photos

## Customize

Edit the `products` array near the bottom of `index.html` to change the sample catalog. Each product has an id, brand, name, category, price, original price, rating, and an Unsplash photo id.

This project is frontend-only: it has no account system, inventory service, checkout, or payment processing. Browser storage is local to the current device and browser.
