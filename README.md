# MS Plate Weight Calculator

A lightweight, single-page web app that calculates the weight of mild steel (MS) plates from their dimensions. Enter length, width, thickness and material density, and get an instant, accurate weight result — handy for fabrication shops, procurement, and engineering estimates.

## Features

- Instant plate weight calculation: weight = length × width × thickness × density
- Adjustable steel density (defaults to the standard 7850 kg/m³)
- Metric inputs (mm) with results in kilograms
- Clean, responsive card-based UI built with vanilla CSS (Poppins typeface)
- Fully client-side — no backend, no dependencies, works offline
- Single self-contained HTML file — easy to host anywhere

## Tech Stack

- HTML5, CSS3, vanilla JavaScript
- Google Fonts (Poppins)

## Quick Start

Open `ms-plate-calculator.html` (or `index.html`) directly in any modern browser — no build step or server required:

```bash
# optional: serve locally
npx serve .
```

Then fill in the plate dimensions and hit calculate.

## Project Structure

```
.
├── ms-plate-calculator.html   # original calculator page
├── index.html                 # entry point served by GitHub Pages
├── README.md
└── LICENSE
```

## Deployment

Deployed as a static site via GitHub Pages: `index.html` is served from the `main` branch root.

## Use Cases

- Fabrication/boiler shop weight estimates for MS plates
- Material costing and purchase quantity planning
- Quick engineering checks on drawing plates

## License

See `LICENSE`.

---

Built by Girish Lade — https://ladestack.in
