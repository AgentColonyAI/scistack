# SciStack

16 interactive scientific calculators in a single HTML file. No build step, no dependencies, no data leaves your browser.

**[Live Demo](https://yourusername.github.io/scistack)**

---

## Calculators

| Category | Calculators |
|----------|------------|
| **Math** | Quadratic Solver, Statistics, Geometry (7 shapes), Trigonometry, Unit Converter |
| **Physics** | Kinematics, Projectile Motion, Force/Newton, Energy & Work, Ohm's Law, Waves, Ideal Gas Law |
| **Chemistry** | Molarity, pH Calculator, Half-Life |
| **Biology** | Population Growth (exponential + logistic) |

## Usage

Open `index.html` in any browser. No install required.

```bash
git clone https://github.com/yourusername/scistack
open scistack/index.html
```

## Deploy to GitHub Pages (free)

1. Fork this repo
2. Go to **Settings → Pages**
3. Set source: **Deploy from branch → main → / (root)**
4. Live at `https://yourusername.github.io/scistack`

## Deploy to Netlify

Drag and drop `index.html` at [netlify.com/drop](https://app.netlify.com/drop) — done in 10 seconds.

## Deploy to Vercel

```bash
npm i -g vercel && vercel --yes
```

## Features

- **16 calculators** across math, physics, chemistry, and biology
- **Live sliders** — all charts update in real time
- **Dark mode** toggle
- **Geometry** — circle, rectangle, triangle, sphere, cylinder, cone, cube
- **Unit Converter** — length, mass, temperature, speed, energy, pressure
- **Statistics** — add/remove data points interactively, live distribution chart
- **Population Growth** — toggle logistic (carrying capacity K) vs exponential
- Fully responsive, sidebar collapses on mobile
- Zero data sent anywhere — runs entirely in the browser

## Adding a Calculator

1. Add a nav item in the sidebar with `data-calc="yourname"`
2. Add `<section class="calc-section" id="calc-yourname">` in the content area
3. Write a `calcYourname()` function
4. Register it in the `calcFns` object

## Companion Project

Check out [CalcStack](https://github.com/yourusername/calcstack) — 12 financial calculators, same single-file approach.

## License

MIT — use it, fork it, ship it.
