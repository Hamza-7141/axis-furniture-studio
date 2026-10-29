# AXIS Furniture — Spaces, Thoughtfully Made

A responsive furniture and interior-design showcase with warm green styling, product imagery and a clean multi-page experience.

[Visit the live AXIS Furniture showcase](https://axis-furniture-studio.vercel.app/)

## Explore the project

- Home: furniture highlights and interior inspiration.
- Collection: sample seating cards with accessible product-detail dialogs.
- About: design approach and illustrative team profiles.
- Services: interior and furniture service concepts.
- Inspiration: sample editorial cards.
- Information: explains this portfolio demonstration and its privacy choices.
- Responsive Bootstrap navigation and a locally bundled testimonial slider.

This is a **portfolio catalogue**, not an operating shop. Prices, people, testimonials and service claims are illustrative template content. No orders, stock checks, payments, login, newsletter signup or contact submission are provided. Former cart, checkout and thank-you routes show catalogue information instead.

## Privacy

No forms requesting personal details, analytics, tracking, browser storage, database or backend. Product dialogs use browser memory only. Fonts use the system stack; Bootstrap, Tiny Slider, CSS and images are included locally. The hosted site requests its own static files from Vercel, whose ordinary infrastructure logging is outside this application's control. The footer attribution link contacts its destination only when followed.

## Run locally

No dependencies or build step. Open `index.html` directly, or, with Python installed:

```powershell
python -m http.server 8000 --bind 127.0.0.1
```

Visit http://127.0.0.1:8000 and stop with Ctrl+C.

## Structure

`*.html` — pages and catalogue information routes; `css/` — Bootstrap, original theme and AXIS additions; `js/` — local vendors, slider and accessible product dialog; `images/` — included design imagery; `vercel.json` — static hosting and response headers.

## Verification

Run `node --check js/custom.js` and `node --check js/axis.js`. Validate internal asset/page references and inspect mobile navigation and product dialogs before changes are published. Automated source audit checks for forms, persistent storage and external runtime scripts. Hosting checks and any visual-test limitations are reported separately.

## Credits and licensing

Adapted from **UntreeStore / Furni by Untree.co**, supplied with a CC BY 3.0 attribution notice in `css/style.css`. The original template credit remains in the website footer and source. Bootstrap and Tiny Slider retain their upstream licenses in bundled vendor files. Included imagery is inherited from the supplied template; no exclusive rights or original photography are claimed. Review image rights before commercial reuse.
