# Spoon Blade Shape Generator

A browser tool for designing kayak and canoe paddle blade outlines (Euroblade, spoon / asymmetrical, canoe) and printing them as **full-size templates**.

**Live app:** https://gusmerckel.github.io/SpoonbladeshapeGenerator/

## Features

- **Starting shapes:** symmetrical Euroblade, asymmetrical spoon (touring), compact Euroblade (kids/youth), Northwoods canoe, Beavertail canoe.
- **Step 1 – Nodes:** sliders (or drag on the grid) for the height and width of 5 nodes per side, plus blade length, shaft diameter and printed shaft length.
- **Step 2 – Curvature:** Bézier-style tension and angle per node, neck and tip, with draggable handles.
- **Symmetrical / asymmetrical** toggle, editing each side independently, with tip offset and tilt.
- **1 cm grid** with 5 cm major lines, live width, length and blade area.
- **Printable PDF** at 1:1 scale on A4 or A3, tiled automatically with overlap, cut lines, sheet labels, a 10 cm scale-check bar on every page and a cover page with the sheet map.
- **SVG export** at 1:1 (mm) for laser cutters and CNC.

## Printing

Print at **100% / Actual size** (not "Fit to page") and check that the 10 cm bar measures exactly 10 cm before cutting.

The template gives the blade's front-view outline only; the spoon curve of the side profile is shaped when carving or laminating.

Single self-contained `index.html`: no build step and no dependencies.
