# Café de la Loma - Menu Web

This project is a simple static website representing the menu for a coffee shop called "Café de la Loma". It is built using basic HTML and CSS and includes a responsive layout for displaying product cards categorized under different sections.

## 📁 Project Structure

```
/ejercicio-clase-M2-3/
│
├── index.html              # Main landing page (if any)
├── menu.html               # Menu interface (translated to English)
├── styles-menu.css         # Specific styles for the menu page
├── style.css               # General styles (used in other pages)
├── assets/                 # Image files for products and decorations
│   ├── caliente/           # Hot beverage images
│   ├── frio/               # Cold beverage images
│   └── acompa/             # Side dish images
└── README.md               # This documentation
```

## 🌐 Pages Overview

### menu.html

This page lists coffee shop items categorized in three groups:

* Hot Beverages
* Cold Beverages
* Side Dishes

Each item is displayed in a card format:

* Image
* Name
* Description
* Price
* "Buy Now" button (currently static)

## 🎨 Styling

The `styles-menu.css` file contains a grid layout for item cards, along with typography and spacing styles. It uses a custom font from Google Fonts.

## 🔧 How to Modify

If you want to update the menu in the future:

1. **Add/Remove Products:**

   * Copy a card `<div class="card">...</div>` block.
   * Replace image paths, names, and descriptions accordingly.
2. **Update Prices:**

   * Locate `<section class="price"><h3>$...</h3></section>` and change the value.
3. **Translate Again:**

   * Use the `lang` attribute in `<html lang="...">`.
   * Adjust section headings and product names.
4. **Change Styles:**

   * Modify `styles-menu.css` to change layout or colors.

## 📝 Notes for Similar Future Projects

* Use semantic HTML5 (`<header>`, `<main>`, `<section>`) for clear structure.
* Keep content organized in cards with consistent class naming.
* Maintain a clear file structure (assets for images, separate CSS).
* Use `lang` and `<meta charset="UTF-8">` for internationalization.
* Use CSS Grid or Flexbox for layout.

## 🛠️ Requirements

No external dependencies are required to run the project. Simply open `menu.html` in a browser.

## 📸 Assets Attribution

All images are locally stored under `/assets/` and organized by category.
