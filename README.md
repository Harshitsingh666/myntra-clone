# Myntra Clone 🛍️

A simple Myntra-style shopping website built with plain **HTML, CSS and JavaScript**.

> ⚠️ **Educational project only.** This is a learning replica. It is not affiliated with, endorsed by, or connected to Myntra. Brand names are used for practice purposes only.

## Features

- Sticky navbar with category tabs (All, Men, Women, Kids, Footwear)
- Live product search
- Product grid with price, MRP and discount %
- Wishlist (heart) toggle with counter
- Shopping bag side panel: add, remove, and total price
- Responsive layout for mobile screens

## Tech Stack

- HTML5
- CSS3 (Grid, Flexbox)
- Vanilla JavaScript (no frameworks, no libraries)

## Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/YOUR-USERNAME/myntra-clone.git
   ```
2. Open the folder
   ```bash
   cd myntra-clone
   ```
3. Open `index.html` in your browser (double-click it, or use the **Live Server** extension in VS Code).

No installation or build step needed.

## Project Structure

```
myntra-clone/
├── index.html    # the whole website (HTML + CSS + JS)
└── README.md     # this file
```

## How It Works

- Products are stored in a JavaScript array called `products`. Add or edit items there.
- `showProducts()` filters the array by category and search text, then draws the cards.
- The wishlist and bag are simple arrays of product ids. Every change redraws the UI.

## Future Improvements

- [ ] Save the bag using `localStorage`
- [ ] Product detail page
- [ ] Size selector
- [ ] Sort and filter by price
- [ ] Login / signup page

## Disclaimer

This project is made for learning web development. Product images come from [picsum.photos](https://picsum.photos) and are random placeholders.

## Author

Made by **Harshit**, B.Tech CSE (Cyber Security), SRMU Lucknow.
