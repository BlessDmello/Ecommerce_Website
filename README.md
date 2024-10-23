
# E-commerce Website

## Overview
This project is a fully responsive e-commerce website built using HTML, CSS, and JavaScript. It allows users to view products, add items to the cart, and manage their shopping experience. The cart functionality is powered by JavaScript and uses local storage to maintain the state across different pages.

## Features
- **Dynamic Product Cards**: Rendered using JavaScript.
- **Add to Cart**: Allows users to add/remove products, with quantity controls.
- **Local Storage**: Stores cart items and quantities.
- **Toast Notifications**: User-friendly alerts for actions like adding/removing products.
- **Responsive Design**: Optimized for all screen sizes.
- **Multiple Pages**: Includes About, Contact, Product pages, and a Cart system.

## Pages & Structure
- **index.html**: Home page featuring product cards.
- **addToCart.html**: Page to view items added to the cart.
- **about.html**: Company information.
- **contact.html**: Contact form.
- **products.html**: Product details.

## JavaScript Functionality
- **Dynamic Cards**: `homeProductCards.js` dynamically generates product cards.
- **Cart Management**: `addToCart.js`, `removeProdFromCart.js`, and `incrementDecrement.js` handle adding, removing, and adjusting quantities.
- **Local Storage**: `getCartProducts.js`, `updateCartValue.js`, and `fetchQuantityFromCartLS.js` manage cart items in local storage.
- **User Feedback**: `showToast.js` shows toast notifications for cart actions.

## Styles
- **style.css**: Main stylesheet, ensuring a clean and responsive layout across devices.

## How to Use
1. Clone this repository.
   ```bash
   git clone https://github.com/BlessDmello/Ecommerce_Website.git
   ```
2. Open `index.html` in your browser to view the homepage.

## Future Improvements
- Add product filtering and search functionality.
- Integrate backend with a database for product management.

