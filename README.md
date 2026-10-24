# Wall Art Cropper

Browser tool that crops images into standard wall-art print sizes at 300 DPI and exports max-quality JPEGs (single files or a zip).

When the source is too small for the largest selected size, it is upscaled ×2 or ×4 with an ESRGAN model ([UpscalerJS](https://upscalerjs.com)) before cropping. Everything runs locally in the browser; no images leave your machine.

**Use it:** https://asanserra.github.io/wall-art-cropper/

Sizes — portrait: 4×6, 5×7, 8×10, 11×14 · landscape: 9×12, 16×20, 18×24, 24×36, A2.

Run locally by opening `index.html`, or `python3 -m http.server` in this folder.
