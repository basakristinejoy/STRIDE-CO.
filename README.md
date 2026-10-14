# STRIDE CO. Shoe Shop

A responsive, single-page shoe shopping website built with **HTML, CSS, and JavaScript**. STRIDE CO. showcases a collection of footwear in a clean, modern storefront where visitors can browse products, filter by category, search for shoes, save favorites, and manage a demo shopping bag.

**Live website:** (https://basakristinejoy.github.io/STRIDE-CO./)

**Student:** KRISTINE JOY M. BASA  
**Year and Section:** _Add your year and section_

---

## Features

- **Responsive layout** — adjusts for desktop, tablet, and mobile screens.
- **Product catalog** — displays eight shoe styles with product images, names, categories, and prices.
- **Category filters** — browse All Shoes, Running, Lifestyle, or Slip-on.
- **Search** — find products by shoe name or category.
- **Favorites** — tap the heart button to mark or unmark favorite products.
- **Demo shopping bag** — add products, remove products, and view item quantities and the running total.
- **Interactive feedback** — toast messages confirm actions such as adding an item to the bag.
- **Store information** — includes a brand introduction, shopping highlights, and footer navigation.
- **Single-file setup** — HTML, CSS, and JavaScript are all contained in `index.html`.

## Technologies Used

- **HTML5** for page structure and content.
- **CSS3** for styling, layout, responsive design, and hover effects.
- **Vanilla JavaScript** for product rendering, category filtering, search, favorites, and shopping-bag interactions.
- **External image URLs** for shoe photography.

No frameworks, package installation, or build tools are required.

## Project Structure

```text
STRIDE-CO-SHOE-SHOP-/
└── index.html    # Complete website (HTML, CSS, and JavaScript)
```

## Run Locally

1. Download or clone this repository.
2. Open the project folder.
3. Open `index.html` in a modern web browser.
4. Ensure you have an internet connection to load the external product images.

You can also use a local development extension such as Live Server in Visual Studio Code, but it is not required.

## Deploy with GitHub Pages

1. Push `index.html` to the root of the GitHub repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select the `main` branch and `/(root)` folder, then save.
5. Wait for GitHub Pages to finish deploying.
6. Visit: https://basakristinejoy.github.io/STRIDE-CO-SHOE-SHOP-/

If the repository uses a different default branch, choose that branch instead.

## Product Collection

The demo catalog includes these products:

| Product | Category | Price |
|---|---|---:|
| Trailhead Runner | Running | ₱2,890 |
| Marathon Pro | Running | ₱3,490 |
| Boulevard Low | Lifestyle | ₱2,590 |
| Cloudstep Slip-On | Slip-on | ₱1,990 |
| City Pace | Lifestyle | ₱2,390 |
| Velocity Knit | Running | ₱3,190 |
| Weekend Classic | Lifestyle | ₱2,290 |
| Drift Slip-On | Slip-on | ₱1,890 |

Prices are sample values for the demonstration and can be edited in the `products` array inside `index.html`.

## Important Limitations

- The shopping bag is stored only in the current page session and is not connected to a database.
- Checkout is a demonstration only. The application does **not** process payments or place real orders.
- Favorites are not saved permanently.
- Product images are hosted externally and may require internet access; an image fallback is provided if a product image fails to load.
- There is no customer account, inventory management, or admin dashboard.

## Customization

To update the website, edit `index.html`:

- **Product names, categories, prices, and image URLs:** find the `products` array in the `<script>` section.
- **Colors and styling:** edit the CSS variables near the top of the `<style>` section.
- **Brand text and page sections:** edit the HTML inside `<body>`.
- **Store year:** the footer year updates automatically.

## Future Improvements

Possible enhancements include connecting a database, persistent favorites and carts, product detail pages, customer accounts, stock tracking, and a secure payment gateway.

---

Made as a web development project by **KRISTINE JOY M. BASA**.
