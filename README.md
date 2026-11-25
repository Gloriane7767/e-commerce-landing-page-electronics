# GloMobile — Electronics E-Commerce Landing Page

A polished, responsive electronics storefront landing page built with HTML and Tailwind CSS. GloMobile presents featured mobile accessories, a product showcase, customer reviews, promotional calls to action, and a complete store-style footer.

## Preview

Open `index.html` directly in a browser, or serve the project with a local HTTP server.

## Features

- Responsive navigation header
- Product hero and limited-offer badge
- Featured electronics and accessory cards
- Product showcase with gallery and quantity selector
- Customer review section
- Promotional shop-now call to action
- Newsletter and account footer links
- Mobile-friendly layout using Tailwind CSS

## Tech Stack

- **HTML5** — Semantic page structure
- **Tailwind CSS** — Utility-first styling via CDN
- **Unsplash, Pexels, and Flaticon** — Product, review, and social imagery
- **Vanilla SVG** — Icons for the header and navigation

## Project Structure

```text
.
├── index.html                         # Complete landing page
└── e-commerce-landing-page-demo.iml   # IntelliJ project metadata
```

## Getting Started

No build tools or package installation are required.

### Option 1: Open directly

1. Clone the repository:

   ```bash
   git clone https://github.com/Gloriane7767/e-commerce-landing-page-electronics.git
   ```

2. Open `index.html` in your browser.

### Option 2: Use a local server

Using Python:

```bash
cd e-commerce-landing-page-electronics
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

Using VS Code, you can also open the project with the Live Server extension.

## Customization

- Update page copy and product details in `index.html`.
- Replace external image URLs in the `<img>` elements with local assets or your preferred CDN.
- Adjust the Tailwind utility classes to change colors, spacing, typography, and layout.
- Update navigation links, review content, and footer information as needed.

## Demo Status

This repository is a frontend demonstration. The cart, wishlist, Buy Now and Subscribe controls, navigation links, quantity state, and newsletter form are currently visual elements and do not include persistent data or backend integration.

## Deployment

The project can be deployed as a static site with GitHub Pages or any static hosting provider. Deploy the repository root and use `index.html` as the entry point.

## License

No license has been specified for this project. Please add a license before reuse or redistribution.
