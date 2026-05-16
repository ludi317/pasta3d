# pasta3d

Interactive 3D parametric pasta viewer with live sliders. Ten shapes,
several ported directly from George L. Legendre's *Pasta by Design*
(Thames & Hudson, 2011).

## Run

Open `index.html` in any modern browser. No build step.

## Controls

- Drag to orbit, scroll to zoom (over the canvas)
- Click a pasta name to switch shapes; per-shape sliders appear below
- Reset button restores defaults for the current shape

## Shapes

Ported from Legendre's exact equations:

- **Farfalle** — p.63
- **Mafaldine** — p.114
- **Rotelle** — p.152

Hand-built parameterizations (not from the book):

- **Fusilli** — N-blade helical ribbon, twist + curl + thickness
- **Cavatappi** — Frenet-frame tube swept along a helix, with rib ornamentation
- **Penne** — cylinder cut by parallel oblique planes, with rigate ridges
- **Macaroni** — bent tube on a planar arc
- **Gemelli** — two tubes winding around a shared axis
- **Gnocchi** — ridged spheroid with thumbprint indent
- **Spaghetti** — drooping/wobbling tube swept by Frenet frame

## Credit

Slider/p5.js scaffolding adapted from
[conch3d](https://github.com/ludi317/conch3d).
Pasta equations are from George L. Legendre,
*Pasta by Design* (Thames & Hudson, 2011).
