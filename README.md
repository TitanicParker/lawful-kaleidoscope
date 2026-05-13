# Lawful Kaleidoscope

A browser-native lawful, kaleidoscopic, never-ending pattern generator based on a 60 degree hexagonal / MN field.

The first prototype is deliberately simple: a single `index.html` file that runs directly in the browser and can be hosted by GitHub Pages.

## What it does

- Draws a faint 60 degree tri-hex field.
- Generates continuous kaleidoscopic motion.
- Supports 6-fold and 12-fold symmetry.
- Includes three seed modes: Bloom, Weave, and Pocket.
- Uses corrective drift so patterns remain coherent rather than dissolving into pure noise.
- Provides controls for density, speed, pulse, correction strength, trails, and symmetry.
- Supports PNG export.

## Controls

- `Space`: pause or resume
- `R`: create a new lawful seed
- `H`: show or hide the control panel

## Project direction

This repository is intended to become a lawful geometry toy and visual field laboratory. The near-term path is:

1. Keep the single-file prototype working.
2. Add GitHub Pages hosting.
3. Split the code into `style.css`, `engine.js`, `geometry.js`, and `patterns.js` once the behavior stabilizes.
4. Add clearer MN-coordinate inspection.
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
