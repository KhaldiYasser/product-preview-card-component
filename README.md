# 🛍️ Product Preview Card Component

A responsive, beautifully styled e-commerce product preview card built using **HTML5** and **CSS3**. The component is designed to adapt its layout and display appropriate image assets based on the device's screen size[cite: 24, 25].

---

## 📸 Features

* **Responsive Design:** Uses CSS Grid for a side-by-side desktop layout and automatically switches to a stacked vertical layout on screens smaller than 700px via media queries.
* **Art Direction (Responsive Images):** Utilizes the HTML5 `<picture>` element to dynamically serve `image-product-desktop.jpg` on large screens and `image-product-mobile.jpg` on mobile devices.
* **Custom Typography:** Integrates **Fraunces** (for headings and prices) and **Montserrat** (for body text) via Google Fonts[cite: 24, 25].
* **UI Details:** Includes an original price strikethrough using the `<del>` tag, an SVG cart icon inside the "Add to Cart" button, and specific HSL color coding for accurate branding[cite: 24, 25].

---

## 🛠️ Built With

* **HTML5** - Semantic layout, typography links, and `<picture>` tags[cite: 24].
* **CSS3** - CSS Grid (`display: grid`), Flexbox, media queries (`@media`), and border-radius manipulation for responsive corners.

---

## 📁 Project Structure

```text
.
├── index_6.html        # Main HTML file containing the product content and font links[cite: 24]
├── style.css           # Styling rules, Grid/Flexbox layouts, and breakpoints[cite: 25]
└── images/             # Image assets directory[cite: 24]
    ├── image-product-desktop.jpg[cite: 24]
    ├── image-product-mobile.jpg[cite: 24]
    └── icon-cart.svg[cite: 24]