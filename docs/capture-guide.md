# Capture guide — shooting photos & video for Gaussian Splatting

The quality of a 3D Gaussian Splat depends mostly on the input. These tips apply to
RadianceKit and to any Gaussian Splatting workflow on a Mac.

## The basics

- **Coverage:** circle the subject and shoot from many angles — low, eye-level, and
  high. Aim for 30–200 photos for an object, more for a room or large scene.
- **Overlap:** each photo should overlap the previous one by ~60–80%. Move in small
  steps; don't teleport between viewpoints.
- **Sharpness:** avoid motion blur. Use enough light or a faster shutter. Blurry
  frames hurt camera alignment.
- **Lighting:** keep it consistent. Diffuse, even light is ideal; avoid changing
  exposure mid-capture and harsh moving shadows.
- **Stay still subjects:** the scene must not move during capture. People, pets,
  leaves in wind, and reflections/water reduce quality.

## Photos vs. video

- **Photos** give you the most control over coverage and sharpness — best results.
- **Video** is faster to capture: move slowly and steadily, then let the app sample
  frames. Slower motion = sharper frames = better splats.

## Hard cases

- **Reflective / transparent / textureless surfaces** (glass, mirrors, plain white
  walls) are difficult — add context around them and capture more angles.
- **Large scenes:** keep a consistent distance and orbit in passes (e.g. a low ring,
  then a higher ring).

## On a Mac

RadianceKit handles alignment, training, editing, and export from these captures
locally on the Apple Silicon GPU. See the
[full guide](https://radiancekit.de/gaussian-splatting-mac/) and the
[user guide](https://radiancekit.de/guide/).
