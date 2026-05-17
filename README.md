# E-ink Image Converter

A browser-based tool for converting images to PNG for e-ink devices. No uploads, no dependencies — everything runs locally in your browser.

**[Open the tool](https://taoist22.github.io/eink-image-converter/)**

## Device Presets

| Device | Resolution |
|--------|-----------|
| Xteink X4 | 480 × 800 |
| Boox Palma 2 | 824 × 1,648 |
| Supernote Nomad / A6 X / reMarkable 2 / Kobo Elipsa | 1,404 × 1,872 |
| Kindle Scribe | 1,860 × 2,480 |
| Boox Go 10.3 | 2,480 × 1,860 |
| Supernote Manta | 1,920 × 2,560 |
| reMarkable Paper Pro | 2,160 × 2,880 |
| Custom | user defined |

## Features

- **Device presets** — one click to set output dimensions; width and height remain freely editable with optional aspect ratio lock
- **Fit modes** — Fit, Fill, Stretch, Blur-extend (fills letterbox areas with a blurred version of the image)
- **Crop tool** — draggable handles with optional lock-to-output-ratio
- **Alignment grid** — 3×3 positioning for Fit and Fill modes
- **Color depth** — 8-bit, 4-bit, 1-bit
- **Adjustments** — brightness, contrast, grayscale, invert
- **Rotate** — 90° CW / CCW
- **Background fill** — color picker or blur-extend background
- **Editable output filename** — pre-filled from the uploaded file

## Privacy

Images are processed entirely in your browser and never uploaded anywhere.

## Credits

Inspired by [Jake Green's X4 Wallpaper Converter](https://jakegreen.dev). Successor to [nomad-image-converter](https://github.com/taoist22/nomad-image-converter).
