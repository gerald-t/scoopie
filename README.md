# Scoopie 🍰

A warm, responsive website for **Scoopie**, a dessert shop featuring cakes, cookies and ice cream.

## What's included

- Single-page homepage with Home, Our Menu, Our Story and Find Us sections
- Product catalogue for the current menu:
  - **Cakes:** Tiramisu, Burnt Cheesecake, Matcha Cheesecake
  - **Cookies:** Butter, Matcha, Chocolate
  - **Ice cream:** Vanilla, Matcha, Chocolate
- Coming-soon area for future drinks and desserts
- Responsive mobile navigation
- Lightweight scroll-reveal effects
- No framework, build step or database required

## Project structure

```
scoopie/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── README.md
```

## Preview locally

Open `index.html` in a browser. For a local server, you can use the VS Code Live Server extension or run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Open the repository's **Settings**.
2. Select **Pages** in the sidebar.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**, then save.
5. GitHub Pages will publish the site at `https://gerald-t.github.io/scoopie/` once the deployment completes.

## Before opening to customers

- Replace the illustrative stock photos with Scoopie's own product photography.
- Add the store's real address, opening hours and contact/social links.
- Confirm product descriptions and current availability.
- Add prices only when the menu and pricing are final.

The site intentionally does not include online ordering, a cart or payment processing in this first version.
