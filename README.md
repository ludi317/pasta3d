
# pasta3d

Interactive 3D parametric pasta viewer with live sliders. Ten shapes.
<img width="1070" height="751" alt="Screenshot 2026-05-19 at 8 08 16 PM" src="https://github.com/user-attachments/assets/c2dde933-1177-456b-a8bf-cc70494ac64c" />

## Run

Open `index.html` in any modern browser. No build step.

## Controls

- Drag to orbit, scroll to zoom (over the canvas)
- Click a pasta name to switch shapes; per-shape sliders appear below
- Reset button restores defaults for the current shape

## Shapes

Ported from from George L. Legendre's *Pasta by Design*
(Thames & Hudson, 2011):

- **Fusilli** — single-blade helicoid (rotating, climbing bowed bar)
- **Cavatappi** — toroidal tube with 7-fold ribbing, helical climb
- **Farfalle** — bowtie with central pinch and crenellated edges (p.63)
- **Gnocchi** — semi-open ridged shell
- **Mafaldine** — flat ribbon with rippled long edges (p.114, thickened)
- **Rotelle** — wagon-wheel: 6-spoke hub + 91/93-rippled rim (p.152)

Hand-built parameterizations (not from the book):

- **Penne** — cylinder cut by parallel oblique planes, with rigate ridges
- **Macaroni** — bent tube on a planar arc
- **Gemelli** — two tubes winding around a shared axis
- **Spaghetti** — drooping/wobbling tube swept by Frenet frame

## Credit

Slider/p5.js scaffolding adapted from
[conch3d](https://github.com/ludi317/conch3d).
Pasta equations are from George L. Legendre,
*Pasta by Design* (Thames & Hudson, 2011).
