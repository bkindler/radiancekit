# RadianceKit export formats

RadianceKit exports 3D Gaussian Splatting scenes to every common format, plus video
and a self-contained web viewer. Here is what each one is and when to use it.

| Format | Type | Best for |
|--------|------|----------|
| **PLY** | Point/splat data | Maximum compatibility; most splat tools and viewers read it. |
| **Compressed PLY** | Compact PLY | Same as PLY but much smaller files for storage/transfer. |
| **SPZ** | Compressed splat | Efficient, web-friendly splat format (Niantic). Great for sharing. |
| **glTF** | 3D interchange | Bringing scenes into general 3D / engine pipelines that speak glTF. |
| **.splat** | Web splat | Lightweight format used by many browser-based splat viewers. |
| **SOG** | Self-organizing Gaussians | Highly compressed representation for compact delivery. |

## Plus

- **Orbit video** — a rendered fly-around clip (MP4) for quick previews and social posts.
- **Web viewer** — a self-contained, interactive viewer you can host anywhere and share
  by link; no extra software needed to open it.

## Choosing a format

- **Share with anyone / archive:** Compressed PLY or SPZ.
- **Put it on the web:** `.splat`, SPZ, or the built-in web viewer.
- **Move into a 3D/engine pipeline:** glTF.
- **Smallest file:** SOG or Compressed PLY.
- **Widest tool support:** PLY.

See also: [Gaussian Splatting on a Mac — full guide](https://radiancekit.de/gaussian-splatting-mac/).
