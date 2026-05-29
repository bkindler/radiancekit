# RadianceKit — 3D Gaussian Splatting on a Mac

**RadianceKit** is a native macOS app for **3D Gaussian Splatting**: turn ordinary
photos or video into photorealistic, explorable 3D scenes — trained locally on the
Apple Silicon GPU (Metal). No command line, no Python, no cloud.

- 🌐 Website: <https://radiancekit.de>
- 📥 Mac App Store: <https://apps.apple.com/app/radiancekit/id6760346035>
- 📖 Full guide — *Gaussian Splatting on a Mac*: <https://radiancekit.de/gaussian-splatting-mac/>

This repository collects **open documentation and resources** for RadianceKit and for
doing 3D Gaussian Splatting on macOS in general: an export-format reference, a capture
guide, and an FAQ. The app itself ships through the Mac App Store.

## What RadianceKit does

- **The complete workflow in one app:** import → align → train → edit → export.
- **Fully local:** Gaussian Splatting training runs on the Apple Silicon GPU (M1–M4)
  via Metal. Your photos and 3D scenes never leave your device — no account, no cloud.
- **Two modes:** Simple Mode (import, press Start, get a scene) and Expert Mode (3D
  viewport, training inspector, live loss curves, interactive splat editor).
- **Open exports:** PLY, Compressed PLY, SPZ, glTF, `.splat`, SOG — plus orbit videos
  and self-contained, shareable web viewers.

## Requirements

- Apple Silicon Mac (M1 or later)
- macOS 26 Tahoe or later
- 16 GB RAM recommended

## How 3D Gaussian Splatting works

1. **Capture** — 30–200 overlapping photos (or a slow video) from many angles.
2. **Align** — camera poses are computed automatically (Apple Photogrammetry).
3. **Train** — Gaussian Splatting builds millions of tiny 3D ellipsoids ("splats").
4. **Preview** — explore the reconstruction from any angle in real time.
5. **Export** — save to a standard format or share as a web viewer.

## Documentation

- [Export formats](docs/export-formats.md) — PLY, SPZ, glTF, `.splat`, SOG and when to use each.
- [Capture guide](docs/capture-guide.md) — how to shoot photos/video for clean splats.
- [FAQ](docs/faq.md) — hardware, privacy, pricing, formats.

## Pricing

Free download with a 3-day full-feature trial. After the trial, a one-time in-app
purchase unlocks the full version — no subscription.

## About

Made by Bjoern Kindler. Questions or feedback: <info@kindler-dev.de> · <https://radiancekit.de>

## License

The documentation in this repository is licensed under
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — quote and reference it
freely with attribution. "RadianceKit", the app, and its screenshots remain
© Bjoern Kindler.
