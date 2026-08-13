# DEXI 3 — Realistic 3D Build Visualizer

Interactive 3D build simulator for the **DroneBlocks DEXI 3** (3″ open-source PX4 / ROS 2 drone), in the same spirit as [OA35](https://equationstratos.github.io/OA35/) and [Foldape4](https://github.com/equationstratos/Foldape4).

**Goal:** maximum realism — real dimensions, real chassis plates, motors, electronics stack, camera, landing gear, antenna, correct relative positioning and assembly.

## Official sources

| Resource | Link |
|----------|------|
| Main DEXI repo (ROS 2) | https://github.com/DroneBlocks/dexi |
| 3D printed parts (STEP) | https://github.com/DroneBlocks/dexi-3d-prints/tree/main/dexi-3 |
| Robot description / meshes | https://github.com/DroneBlocks/dexi_robot_description |
| Full simulator (Unity + PX4 + ROS2) | https://github.com/DroneBlocks/dexi-sim-ftw |
| Product page | https://droneblocks.io/product/dexi-3-single/ |
| PX4 project page | https://px4.io/project/dexi/ |

## Hardware (DEXI 3)

- **Frame**: 3″ custom (Top + Bottom Frame Plate)
- **Motors**: RCINPOWER GTS V3 — 4680KV
- **Propellers**: Gemfan 3018 Tri-Blade
- **Typical diagonal**: ~150–160 mm motor-to-motor
- Flight stack: PX4 compatible + companion computer
- Fully open-source airframe + mounts

## Available official 3D parts (STEP)

From `DroneBlocks/dexi-3d-prints/dexi-3`:

- DEXI 3 Top Frame Plate / Bottom Frame Plate
- DEXI 3 Battery Mount
- DEXI 3 Landing Gear
- DEXI 3 Antenna Mount (several versions)
- DEXI 3 RX Mount
- DEXI 3 Pie Cam Mount (arms + plate)
- DEXI 3 LED Ring
- DEXI 3 XT30 + Cap
- DEXI 3 Flow Mounts

## Project status

- [x] Repository created
- [ ] Realistic Three.js viewer with correct scale & positioning
- [ ] Convert key STEP → STL / GLTF for web
- [ ] Motors + props + stack + battery in correct places
- [ ] Assemble / explode / isolate parts (OA35 style)
- [ ] Photo-trace path for any missing geometry

## Live viewer

Enable GitHub Pages (Settings → Pages → main / root) → **https://equationstratos.github.io/DEXI3/**

---
**STRATOS ROBOTICS style project** — same approach as OA35 & Foldape4
