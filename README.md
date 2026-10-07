# SPI&CE design prototype

Local HTML, SCSS and JavaScript prototype, processed by Vite.

```sh
npm install
npm run dev
```

Open http://127.0.0.1:4173. Vite recompiles SCSS and reloads the page as files change.

```sh
npm run build
npm run preview
```

The production output is in `dist/`; preview uses port 4174.

## Editing

- `index.html`: original homepage content and semantic markup.
- `styles.scss`: typography, colors, layout and responsive styles.
- `script.js`: comparison slider, mobile navigation, search dialog and preview forms.
- `images/`: original storefront imagery saved during the design work.
- `assets/`: selected project photos, logo and local fonts.

Preserve the original wording and all sections. See `../DESIGN-CONTENT.md`.

This is a design prototype, not a connected Shopify theme. Product, account, cart and search actions link to the existing store. Prices are the GBP snapshot reviewed on 6 October 2026. Newsletter forms validate email but do not subscribe anyone; they show an explicit preview notice. The region link leads to the original store. No tracking runs in the prototype.

Visual reference: `../Homepage concept 01.png`. Headings use the locally supplied Kings Caslon Trial Regular; body and UI use locally bundled Work Sans. The original store product names and prices are retained, while model-photo layering follows the concept. The bestseller is retained as a label and shop link in the first product card.
