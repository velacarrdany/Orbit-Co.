# Orbit & Co. — Planet Shop

A fictional single-page shopping site for planets. No real purchases, shipping, or ownership involved — just a front-end demo.

## Files

| File | Purpose |
|---|---|
| [PlanetShop.html](https://github.com/velacarrdany/Orbit-Co./blob/main/PlanetShop.html) | Main page markup |
| [styles.css](https://github.com/velacarrdany/Orbit-Co./blob/main/styles.css) | All styling |
| [images/](https://github.com/velacarrdany/Orbit-Co./tree/main/images) | Folder for product and favicon images (add manually) |

## Setup

1. Keep `PlanetShop.html` and `styles.css` in the same folder.
2. Create an `images/` folder next to them.
3. Add the following PNG files to `images/`:
   - [mercury.png](https://github.com/velacarrdany/Orbit-Co./blob/main/images/mercury.png)
   - [venus.png](https://github.com/velacarrdany/Orbit-Co./blob/main/images/venus.png)
   - [mars.png](https://github.com/velacarrdany/Orbit-Co./blob/main/images/mars.png)
   - [jupiter.png](https://github.com/velacarrdany/Orbit-Co./blob/main/images/jupiter.png)
   - [icon.png](https://github.com/velacarrdany/Orbit-Co./blob/main/images/icon.png) (used as the browser tab favicon)
4. Open `PlanetShop.html` in a browser.

## Features

- Product grid with price, stock status, and an "Add to Cart" button (non-functional, for display only)
- Hover animations on each planet card, built with the Web Animations API:
  - **Mercury** — opacity
  - **Venus** — background color
  - **Mars** — rotation
  - **Jupiter** — scale/size

## Notes

- No backend, cart logic, or checkout — this is a static UI mockup.
- Missing images will show as blank/broken until added to `images/`.
