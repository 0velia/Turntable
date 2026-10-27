# Turntable

A browser-based 3D model viewer and converter. Everything runs locally in the browser; no files are uploaded.

## Formats

**Open:** GLB, glTF, OBJ, STL, PLY, DAE, FBX, 3DS, 3MF, AMF, WRL (VRML), KMZ, VTK

**Convert to:** GLB, glTF, OBJ, STL, PLY, DAE

For models with separate texture files (for example a DAE or OBJ), select the model and its textures together.

## Features

- Orbit, pan and zoom viewer with auto-fit
- Shading modes: solid, wireframe, solid + wireframe (adjustable color and opacity) for checking mesh density
- Vertex, triangle and size readout
- Compact DAE writer for dense meshes
- Fallback reader for slicer-style 3MF files

## Run it

It's a single static file. Open `index.html` in a browser, or publish the repo with GitHub Pages
(Settings → Pages → deploy from the main branch, root folder).

An internet connection is needed on first load: three.js, JSZip and fflate come from the jsDelivr and cdnjs CDNs,
and the font from Google Fonts.

## Third-party libraries

three.js (MIT), JSZip (MIT or GPLv3), fflate (MIT), chevrotain (Apache-2.0).
