# DEXI 3 — Realistic 3D Build Visualizer

Interactive 3D build simulator for the **DroneBlocks DEXI 3** open-source drone.
Same approach as [OA35](https://equationstratos.github.io/OA35/) and [Foldape4](https://github.com/equationstratos/Foldape4).

**Live viewer**: enable GitHub Pages → https://equationstratos.github.io/DEXI3/

## Done

- [x] Repository + realistic Three.js viewer (assemble / explode / views)
- [x] Official STEP files downloaded from DroneBlocks/dexi-3d-prints
- [x] Converted all key parts **STEP → ASCII STL** with Gmsh
- [x] Measured real bounding boxes of every part

## Real dimensions (from official STEP)

| Part | Size (mm) |
|------|-----------|
| Top Frame Plate | 204 × 204 × 2 |
| Bottom Frame Plate | 204 × 204 × 2 |
| Landing Gear | 83 × 82 × 14.5 |
| Battery Mount | 70 × 38.5 × 7.7 |
| Antenna Mount V3 | 28.5 × 43 × 8 |
| RX Mount | 27 × 23 × 9 |
| LED Ring | 70 × 70 × 5 |
| Pie Cam Mount + Arms | ~23 × 13 × 25 |
| XT30 | 12 × 23 × 11 |

Frame plates include the full arm / motor-mount envelope.

## Official sources

- Main: https://github.com/DroneBlocks/dexi
- 3D prints (STEP): https://github.com/DroneBlocks/dexi-3d-prints/tree/main/dexi-3
- Simulator: https://github.com/DroneBlocks/dexi-sim-ftw
- Product: https://droneblocks.io/product/dexi-3-single/

## Hardware

- Motors: RCINPOWER GTS V3 4680KV
- Props: Gemfan 3018 Tri-Blade
- Open-source PX4 + ROS 2 stack

## Next

- Load the converted STLs directly into the Three.js viewer for 100 % exact geometry
- Fine-tune relative positioning of every part (camera arms, RX, antenna, landing gear)
- Optional photo-trace path for any missing pieces

---
**STRATOS ROBOTICS** style project
