# sandbranch

Plug-ins and filters for GIMP 3: abandoned GIMP 2 favourites ported
properly (16-bit and float images, GIMP 3 dialogs, tests), and new tools
built as GEGL filters, which GIMP 3 keeps editable on the layer.

## Filters (GEGL, non-destructive)

| Tool | What it does |
|---|---|
| [Adjustments](https://github.com/sandbranch/gegl-adjustments) | Selective Color, Black & White, Blend If and luminosity masks |
| [Presence](https://github.com/sandbranch/gegl-presence) | Clarity, Texture, Dehaze and Whites/Blacks, as in Camera Raw |
| [Equalizers](https://github.com/sandbranch/gegl-equalizers) | Saturation Equalizer and Advanced Unsharp Mask, ported |
| [Color Lookup](https://github.com/sandbranch/gegl-lut) | Apply .cube, .3dl and Hald CLUT LUTs |
| [Depth Blur](https://github.com/sandbranch/gegl-depth-blur) | Blur by a depth map, with bokeh shapes and highlights; successor to Focus Blur |
| [Underwater](https://github.com/sandbranch/gegl-underwater) | Underwater colour correction and marine snow removal |
| [Wavelet Sharpen and Denoise](https://github.com/sandbranch/gegl-wavelet) | The classic wavelet filters, as editable filters |

## Plug-ins

| Tool | What it does |
|---|---|
| [Liquid Rescale TNG](https://github.com/sandbranch/gimp-lqr-tng) | Seam carving with keep, remove and straight painted right in the dialog |
| [Fusion](https://github.com/sandbranch/gimp-fusion) | Exposure fusion, focus stacking and layer alignment, also for microscopy |
| [Layer Effects](https://github.com/sandbranch/gimp-layerfx) | Photoshop-style layer effects as editable layers (layerfx, ported) |
| [Lensfun](https://github.com/sandbranch/gimp-lensfun) | Lens distortion, chromatic aberration and vignetting correction |
| [BIMP](https://github.com/sandbranch/gimp-bimp) | Batch image manipulation |
| [Wavelet Denoise](https://github.com/sandbranch/gimp-wavelet-denoise), [Wavelet Sharpen](https://github.com/sandbranch/gimp-wavelet-sharpen) | The original plug-ins, ported |
| [Liquid Rescale](https://github.com/sandbranch/gimp-lqr) | The original Liquid Rescale, ported faithfully |

## Image forensics

| Tool | What it does |
|---|---|
| [Forensics](https://github.com/sandbranch/gimp-forensics) | Error Level Analysis, JPEG Ghost, noise, clone and resampling detection and more as live filters; JPEG Info; a Workbench; a Content Credentials (C2PA) viewer |

## Game art and links to other programs

| Tool | What it does |
|---|---|
| [GIMP Link for Blender](https://github.com/sandbranch/gimp-blender-link) | Edit a Blender texture in GIMP and send it back live |
| [UV Tools](https://github.com/sandbranch/gimp-uv-tools) | UV layouts from Blender, OBJ and Blockbench as paths and island masks; seam bleed |
| [Pixel Art Scale](https://github.com/sandbranch/gimp-pixel-scale) | hqx, xBR and Scale2x for pixel art, as filters and for whole images |
| [Tileset Export](https://github.com/sandbranch/gimp-tileset-export) | Tilesets for Tiled and Godot: PNG plus tile properties, collision shapes and animations |

## For developers

[gimp-devtools](https://github.com/sandbranch/gimp-devtools):
build and test GIMP 3 plug-ins against the Flatpak GIMP, and the research
behind these tools (which old plug-ins still have users, what GIMP lacks
compared with Photoshop, links with Blender and level editors).

Every repository has its own README with install instructions and a test
suite that runs with one command. Ports keep their original authors and
licences; the original projects are linked from each README.
