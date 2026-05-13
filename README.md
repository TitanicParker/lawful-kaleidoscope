# Lawful Kaleidoscope Toy Cabinet

A browser-native cabinet of lawful 60 degree geometry toys based on the hexagonal / MN field.

The project currently runs as a single `index.html` file so it can be hosted directly by GitHub Pages.

## Toys

1. **Endless Kaleidoscope**  
   A seed is rotated, mirrored, pulsed, and corrected into coherent non-repeating motion.

2. **Tri-Hex Field**  
   Primal 0 degree, +60 degree, and -60 degree line families breathe across the field, with dual-style interference families layered in.

3. **Pocket Manifold**  
   An 83-point bounded lattice animates as a relational object with interior and boundary points.

4. **Harmonic Orbits**  
   Lawful particles follow hex-constrained orbital waves and leave coherent trails.

## Shared controls

- Toy selector
- Mode selector: Bloom, Weave, Cellular
- Symmetry: 6 or 12
- Density / extent
- Speed
- Pulse
- Correction
- Trails / fade
- Save PNG

## Keyboard controls

- `Space`: pause or resume
- `R`: create a new lawful seed
- `H`: show or hide the control panel
- `S`: save PNG
- `1`, `2`, `3`, `4`: switch toys

## Project direction

This repository is intended to become a lawful geometry toy and visual field laboratory. The near-term path is:

1. Keep the single-file toy cabinet working.
2. Add GitHub Pages hosting.
3. Add more toys: compass sweep, dual medians, operator corrector, and live MN-coordinate inspector.
4. Split the code into `style.css`, `engine.js`, `geometry.js`, and `patterns.js` once the behavior stabilizes.
5. Add exportable seed/state JSON.
6. Add formal operator modes later: gradient, divergence, curl, curl*, and the corrector.

## Lawful basis

The visual grammar is based on the 60 degree MN basis:

```text
m = (1, 0)
n = (1/2, sqrt(3)/2)
g = [[1, 1/2], [1/2, 1]]
```

The current prototype uses this as a generative constraint rather than a full formal operator engine. The formal layer can be added gradually.
