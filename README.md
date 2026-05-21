
# pasta3d

Interactive 3D parametric pasta viewer with live sliders. Ten shapes.
<img width="1190" height="766" alt="Screenshot 2026-05-20 at 7 07 09 PM" src="https://github.com/user-attachments/assets/a3ce20da-1104-4626-9dcf-ed0e7cb93ae7" />


## Run

Open `index.html` in any modern browser. No build step.

## Controls

- Drag to orbit, scroll to zoom (over the canvas)
- Click a pasta name to switch shapes; per-shape sliders appear below
- Reset button restores defaults for the current shape

## Shapes

Ported from George L. Legendre's *Pasta by Design*
(Thames & Hudson, 2011):

- **Fusilli** — single-blade helicoid (rotating, climbing bowed bar)
- **Cavatappi** — toroidal tube with 7-fold ribbing, helical climb
- **Farfalle** — bowtie with central pinch and crenellated edges
- **Gemelli** — single tube swept helically with a small open seam
- **Gnocchi** — semi-open ridged shell
- **Lasagna** — flat ribbon with opposite-phase rippled long edges
- **Rotelle** — wagon-wheel: hub ring + N straight spokes + rippled rim

Hand-built parameterizations (not from the book):

- **Penne** — cylinder cut by parallel oblique planes, with rigate ridges
- **Macaroni** — bent tube on a planar arc
- **Spaghetti** — drooping/wobbling tube swept by Frenet frame

Most shapes have a `thickness` slider that converts the surface into a
true hollow tube or thickened slab.

