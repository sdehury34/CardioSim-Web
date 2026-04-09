# CardioSim-Web

Public project page for **CardioSim: Software Pipeline for Echocardiography Patch**.

**Live site**: [https://sdehury34.github.io/CardioSim-Web/](https://sdehury34.github.io/CardioSim-Web/)

## What is this repo?

This repository hosts **only the project website** — a static landing page describing the CardioSim research pipeline. No source code, hardware schematics, or implementation details are included.

## Adding result images

1. Create an `images/` folder in this repo.
2. Copy your result PNGs (ground truth, B-mode reconstruction, performance chart) into `images/`.
3. In `index.html`, replace each `<div class="result-ph">` block with an `<img>` tag:

```html
<!-- Replace this: -->
<div class="result-ph">
  <span>bmode_reconstructed.png</span>
</div>

<!-- With this: -->
<img src="images/bmode_reconstructed.png" alt="B-mode Reconstruction">
```

## Deploying with GitHub Pages

1. Push this repo to `github.com/sdehury34/CardioSim-Web`.
2. Go to **Settings → Pages**.
3. Set source to **Deploy from a branch → main → / (root)**.
4. Site goes live at `https://sdehury34.github.io/CardioSim-Web/` within a few minutes.

## What is NOT in this repo

- No `.py`, `.m`, `.v`, or `.ipynb` source files
- No raw RF data or HDF5 files
- No hardware design files
- No private research notebooks

For enquiries about the research or source code, contact Somashekhar.

## License

Website content © 2026 Somashekhar. All rights reserved.
