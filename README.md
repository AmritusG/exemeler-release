# eXeMeLeR

Turn patterns, symbols and vector art into Resolume Arena Advanced Output — on macOS.

## What is it?

eXeMeLeR takes decorative patterns, symbols and vector graphics (SVG, PDF, EPS/Illustrator) and
turns them into Resolume Arena Advanced Output XML — polygon slices and masks, ready to drop in.
You can generate a pattern or symbol straight from the built-in library, or design your own thing
in Illustrator, Figma, Inkscape or Affinity and convert it in a few seconds.

## Why I made it

Setting up custom output mappings in Resolume by hand is a pain — drawing every shape point by
point eats hours. So I built eXeMeLeR to skip all that. Generate or import a shape, preview it,
export, done. Beziers, polygons, compound paths, self-intersecting fills — it cleans them all up
so Resolume doesn't choke or go red on you.

I've put it through a LOT of testing against all kinds of vector files to make sure they actually
load right in Advanced Output. If you run into a file that won't convert, send it my way — I'll
figure out what's going on and help you out, or patch the app if it needs it.

## Pattern & Symbols Generator

This is the fun part. 54 built-in generators, each with a seed (for structural variation) plus
scale, density, intricacy and symmetry controls — so you basically never get the same thing twice.
Whatever you generate runs through the same Resolume-safe pipeline as imported art.

**Tiling & geometric patterns** — African Kente, Chinese Lattice, Moroccan Zellige, Islamic Girih,
Greek Meander, Greek Guilloche, Japanese Asanoha / Shippo / Wave, Indian Kolam, Samoan Siapo, Hex
Tessellation, Truchet Tiles, Voronoi, Delaunay, Phyllotaxis, Maze, Pixel Grid, Reaction-Diffusion.

**Symbols & sacred geometry** — Flower of Life, Seed of Life, Metatron's Cube, Sri Yantra, Tree of
Life, Dharma Wheel, Tibetan Endless Knot, Hamsa, Yin Yang, Celtic Knot & Spiral, Torus Knot,
Spirograph, Rose Curve, Lissajous, Cymatic, Op Art, Penrose Tiling, Apollonian Gasket, Koch
Snowflake, Sierpinski, Geodesic, Wireframe Cube & Dodecahedron, Concentric Rings, Radial Slices.

**Cultural scripts & glyphs** — Egyptian Glyphs, Maya Glyphs, Cuneiform, Linear B, Phoenician,
Glagolitic, Nordic Runic, Adinkra, Inca Tocapu.

## What it does

✓ Pattern & Symbol Generator – 54 generators with seed / scale / density / intricacy / symmetry
✓ Vector import – SVG, PDF and EPS/Illustrator: paths, polygons, circles, rectangles, lines, bezier curves
✓ Boolean operations – union, subtract, intersect, XOR and divide shapes to build exactly what you need
✓ Slices & masks – export as Resolume polygon slices, masks, or both
✓ Resolume-safe output – self-intersecting, compound and degenerate shapes get cleaned up automatically so nothing crashes or goes red in Advanced Output
✓ Shape management – enable/disable, rename, multi-select and transform shapes, tweak bezier resolution
✓ Canvas setup – set your output resolution (1920×1080, 4K, custom)
✓ Multi-screen – define multiple output screens/projectors
✓ Live preview – zoom, pan and check your shapes before exporting
✓ Project files – save your work and pick it back up later
✓ Direct export – straight to your Resolume Advanced Output folder
✓ Dark & light themes – whatever's easier on your eyes

## Good for

LED wall mapping, projection mapping, stage design, architectural mapping, festival visuals — and
just spinning up some generative slice geometry when you need something quick.

## How it works

1. Generate a pattern/symbol, or design your shapes in Illustrator/Figma and export as SVG (or import a PDF/EPS)
2. Load it into eXeMeLeR
3. Set your canvas size, enable/disable, transform or Boolean-combine shapes
4. Export to your Resolume Arena Advanced Output folder
5. Load the XML in Resolume → Advanced Output

## Download

Grab the latest **`eXeMeLeR-1.0.0.dmg`** from
[Releases](https://github.com/AmritusG/exemeler-release/releases/latest), open it and drag
eXeMeLeR into Applications.

It's signed with my Developer ID and notarized by Apple, so it opens clean. The first time you
launch it macOS will ask once if you're sure (because it came from the internet) — just hit Open.

## What you need

- macOS 14.0 (Sonoma) or newer
- Universal — runs on Apple Silicon and Intel

## What's included

- The eXeMeLeR app for macOS (universal)
- Exported XML loads in Resolume under **Output ▸ Advanced… ▸ Presets ▸ Load…** — drop the files in
  `/Users/<your-username>/Documents/Resolume Arena/Presets/Advanced Output`

A proper quick-start guide is coming, but honestly I've tried to make it explain itself — every
panel collapses and you can drag them wherever you want, flip between one or two columns in the
preview, and save whatever layout you like.

---

© 2026 Amrit Rosell
