# Talos Suite

**A private, JavaScript-first asset creation and animation suite for Three.js games.**

Talos Suite brings my animation editor and Blender Asset Factory under one product. This is a portfolio showcase: the combined source and builds are private and are not distributed.

## One app, three tools

- **Animate:** first-person weapon poses, swing editing, keyframe timing, impact feel and Three.js game-runtime integration.
- **Asset Factory:** Blender asset production, image-to-3D candidate review, validation, optimization and Three.js previews.
- **Ship:** checks finished models against web game budgets, drops them into a game, and keeps a model library and a phone test.

**Current version: 0.4.0** (29 September 2026). The combined suite now runs as one web app, served by a small local server, with a tab for each tool. It is a private in-house build and still in active development.

## Technology

JavaScript and TypeScript, Three.js, Electron and local Node.js services are the primary stack. Blender and Python support asset-production workflows. The original Godot editor/runtime is retained as legacy compatibility rather than the main direction.

Existing component capabilities include animation editing and playback, local game-preview workflows, Blender validation and asset review. The merger does not imply automatic rigging, finished LOD/collision tooling or an automatic asset-to-animation transfer feature.

## Earlier animation editor

These images show the **legacy Godot-based Talos Animate editor**, not the new combined interface. They document the project's earlier animation tooling; suite screenshots will follow after the integrated build is verified.

![Legacy Talos Animate swing dial and weapon preview](assets/talos-animate/swing-dial.png)

| Pose a key | Inspect neighbouring poses |
| --- | --- |
| ![Legacy editor pose controls](assets/talos-animate/posing-a-key.png) | ![Legacy editor onion-skin preview](assets/talos-animate/onion-skins.png) |

## Availability

Talos Suite is a private in-house tool. There is no public combined-suite download, release or support offering. Older separately published components do not constitute the combined app; their existing licences remain unchanged.

Interested in the technology or a collaboration? [Get in touch](mailto:georgekaragioules@gmail.com).

---

[Software and tools](SOFTWARE.md) · [GitHub profile](README.md) · [Personal website](https://georgekaragioules.com/tools)
