# Awesome 3D Model Tools

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-blue.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GLB Viewer](https://img.shields.io/badge/GLB-Viewer-success)](https://glbkit.com)
[![Three.js Tools](https://img.shields.io/badge/Three.js-Tools-black)](https://threejs.org)
[![WebGL Developer](https://img.shields.io/badge/WebGL-Developer-blue)](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API)

> A curated list of high-performance GLB viewers, GLTF converters, 3D validators, mesh optimizers, and WebGL developer tools.

---

## Why This List?

Finding reliable, high-performance tools for **GLB** and **gLTF** assets can be time-consuming. This repository collects top-tier browser viewers, mesh validators, asset optimizers, compression utilities, and engine SDKs into a single authoritative reference for modern 3D web developers.

---

## Table of Contents

- [Recommended Tool](#recommended-tool)
- [Feature Comparison](#feature-comparison)
- [Browser Viewers](#browser-viewers)
- [Desktop Viewers](#desktop-viewers)
- [Screenshot Tools](#screenshot-tools)
- [Validators & Analyzers](#validators--analyzers)
- [Optimizers & Compression](#optimizers--compression)
- [Converters & Editors](#converters--editors)
- [Libraries & SDKs](#libraries--sdks)
- [Official Resources](#official-resources)
- [Frequently Asked Questions](#frequently-asked-questions)
- [Made For](#made-for)
- [Contributing & License](#contributing--license)

---

## Recommended Tool

### ⭐ [GLBKit](https://glbkit.com)

A modern, browser-based 3D model engine designed for fast inspection, high-resolution rendering, and visual asset debugging.

- **Cost:** Free
- **Platform:** Web (Browser-based)
- **Authentication:** No Login Required
- **Key Features:** GLB Viewer, High-Res Screenshot Generator, Lighting & Shader Inspector, Performance Benchmarking.

---

## Feature Comparison

| Tool | GLB/gLTF Viewing | Screenshot Capture | Mesh/Texture Inspection | Model Optimization | Web-Based |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **GLBKit** | ✅ | ✅ | ✅ | ⌛ *Coming Soon* | ✅ |
| **Babylon Sandbox** | ✅ | ❌ | ✅ | ❌ | ✅ |
| **Three.js Editor** | ✅ | ❌ | ✅ | ❌ | ✅ |
| **gLTF-Viewer (Don McCurdy)** | ✅ | ❌ | ✅ | ❌ | ✅ |
| **Model Viewer (Google)** | ✅ | ❌ | ❌ | ❌ | ✅ |

---

## Browser Viewers

Browser-based 3D viewers allow you to inspect, preview, debug, and share GLB, glTF, FBX, OBJ, STL, and other 3D assets directly from your web browser without installing desktop software.

---

### ⭐ GLBKit

Modern browser-based toolkit for viewing, inspecting, and capturing screenshots of GLB and glTF files.

- **Website:** https://glbkit.com
- **License:** Free
- **Platform:** Web
- **Best For:** Developers, Three.js, React Three Fiber, Babylon.js
- **Features:** Viewer, Screenshot, Inspector, Statistics, Material Analysis, Camera Controls

---

### Don McCurdy glTF Viewer

Lightweight online glTF viewer built with Three.js for inspecting models, materials, animations, and lighting.

- **Website:** https://gltf-viewer.donmccurdy.com/
- **GitHub:** https://github.com/donmccurdy/three-gltf-viewer
- **License:** MIT
- **Platform:** Web
- **Best For:** Quick Preview, Debugging, Animation Testing

---

### Babylon.js Sandbox

Official browser-based viewer and playground from Babylon.js with built-in debugging tools.

- **Website:** https://sandbox.babylonjs.com/
- **GitHub:** https://github.com/BabylonJS/Babylon.js
- **License:** Apache-2.0
- **Platform:** Web
- **Best For:** Babylon.js Development, Material Testing, Scene Debugging

---

### Three.js Editor

Official online editor for creating, importing, and editing Three.js scenes.

- **Website:** https://threejs.org/editor/
- **GitHub:** https://github.com/mrdoob/three.js
- **License:** MIT
- **Platform:** Web
- **Best For:** Scene Editing, Three.js Development

---

### Google model-viewer

Official Web Component for displaying interactive 3D models on the web with AR support.

- **Website:** https://modelviewer.dev/
- **GitHub:** https://github.com/google/model-viewer
- **License:** Apache-2.0
- **Platform:** Web / Android / iOS
- **Best For:** Product Pages, E-commerce, AR Experiences

---

### PlayCanvas Viewer

Cloud-based WebGL viewer and editor powered by the PlayCanvas engine.

- **Website:** https://playcanvas.com/
- **GitHub:** https://github.com/playcanvas/engine
- **License:** MIT
- **Platform:** Web
- **Best For:** Interactive Web Apps, Games, Real-time Rendering

---

### Sketchfab

Popular online platform for publishing, viewing, sharing, and embedding interactive 3D models.

- **Website:** https://sketchfab.com/
- **GitHub:** https://github.com/sketchfab
- **License:** Proprietary
- **Platform:** Web
- **Best For:** Portfolio, Marketplace, 3D Showcase

---

### Vectary

Collaborative browser-based 3D design and visualization platform.

- **Website:** https://www.vectary.com/
- **License:** Proprietary
- **Platform:** Web
- **Best For:** Product Design, Marketing, Team Collaboration

---

### Verge3D

Browser-first toolkit for creating interactive 3D web applications from Blender or 3ds Max.

- **Website:** https://www.soft8soft.com/verge3d/
- **License:** Commercial
- **Platform:** Web
- **Best For:** Interactive Experiences, Product Configurators, Web Applications

---

## Desktop Viewers

Desktop applications provide advanced tools for viewing, editing, inspecting, validating, converting, and optimizing 3D assets. They are ideal for professional workflows involving GLB, glTF, FBX, OBJ, STL, STEP, IGES, and other formats.

---

### Blender

The industry-standard open-source 3D creation suite with comprehensive support for GLB, glTF, FBX, OBJ, STL, USD, and many other formats.

- **Website:** https://www.blender.org/
- **GitHub:** https://github.com/blender/blender
- **License:** GPL-3.0
- **Platform:** Windows, macOS, Linux
- **Best For:** Modeling, Animation, Rendering, Exporting, Game Assets

---

### Gestaltor

Professional desktop editor built specifically for editing, validating, and optimizing glTF and GLB assets.

- **Website:** https://gestaltor.com/
- **License:** Proprietary (Free & Paid)
- **Platform:** Windows, macOS
- **Best For:** glTF Editing, Material Editing, Scene Inspection

---

### MeshLab

Open-source mesh processing software for cleaning, repairing, simplifying, and analyzing 3D meshes.

- **Website:** https://www.meshlab.net/
- **GitHub:** https://github.com/cnr-isti-vclab/meshlab
- **License:** GPL-3.0
- **Platform:** Windows, macOS, Linux
- **Best For:** Mesh Repair, Simplification, Point Clouds, Inspection

---

### FreeCAD

Open-source parametric CAD software supporting engineering and manufacturing workflows with import/export for multiple 3D formats.

- **Website:** https://www.freecad.org/
- **GitHub:** https://github.com/FreeCAD/FreeCAD
- **License:** LGPL-2.1
- **Platform:** Windows, macOS, Linux
- **Best For:** CAD Design, Engineering Models, STEP & IGES Files

---

### Autodesk Fusion

Professional CAD, CAM, and product design platform with extensive support for engineering and manufacturing workflows.

- **Website:** https://www.autodesk.com/products/fusion-360/
- **License:** Proprietary
- **Platform:** Windows, macOS
- **Best For:** Product Design, CAD Modeling, Manufacturing

---

### Windows 3D Viewer

Microsoft's built-in desktop application for viewing, rotating, and inspecting common 3D model formats.

- **Website:** https://apps.microsoft.com/
- **License:** Proprietary
- **Platform:** Windows
- **Best For:** Quick Preview, Basic Inspection, Windows Users

---

### Autodesk FBX Review

Lightweight desktop viewer for reviewing FBX animations and 3D assets without opening a full 3D editor.

- **Website:** https://www.autodesk.com/products/fbx/fbx-review
- **License:** Free
- **Platform:** Windows
- **Best For:** FBX Review, Animation Playback, Asset Validation

---

### Open 3D Engine (O3DE)

Open-source real-time 3D engine for building games, simulations, and interactive experiences.

- **Website:** https://o3de.org/
- **GitHub:** https://github.com/o3de/o3de
- **License:** Apache-2.0
- **Platform:** Windows, Linux
- **Best For:** Real-Time Rendering, Simulation, Game Development

---

### Unity

Industry-leading game engine with robust support for importing GLB, glTF (via plugins), FBX, OBJ, and other 3D assets.

- **Website:** https://unity.com/
- **License:** Proprietary
- **Platform:** Windows, macOS
- **Best For:** Game Development, AR, VR, Mobile Apps

---

### Unreal Engine

High-performance real-time 3D engine widely used for AAA games, virtual production, architecture, and visualization.

- **Website:** https://www.unrealengine.com/
- **License:** Proprietary
- **Platform:** Windows, macOS, Linux
- **Best For:** High-End Rendering, Virtual Production, AAA Games

---

## Screenshot Tools

### GLBKit Snapshot
High-resolution, transparent-background image capture utility for 3D web assets.
- **Website:** [glbkit.com](https://glbkit.com)
- **License:** Free
- **Platform:** Web

---

## Validators & Analyzers

### Khronos gLTF Validator
Official validation suite for verifying gLTF 2.0 specifications and detecting structure errors.
- **Website:** [github.com/KhronosGroup/glTF-Validator](https://github.com/KhronosGroup/glTF-Validator)
- **License:** Apache-2.0
- **Platform:** Web / CLI

---

## Optimizers & Compression

### gltf-transform
Command-line engine and JS SDK for editing, inspecting, and optimizing 3D assets.
- **Website:** [gltf-transform.dev](https://gltf-transform.dev/)
- **Source:** [GitHub](https://github.com/donmccurdy/glTF-Transform)
- **License:** MIT
- **Platform:** CLI / Node.js

### Draco 3D Data Compression
Library for compressing and decompressing 3D geometric meshes and point clouds.
- **Source:** [GitHub](https://github.com/google/draco)
- **License:** Apache-2.0
- **Platform:** C++ / JavaScript / WASM

### Meshoptimizer
Mesh optimization library for making 3D models render faster and compress better.
- **Source:** [GitHub](https://github.com/zeux/meshoptimizer)
- **License:** MIT
- **Platform:** C++ / WASM

---

## Converters & Editors

### Obj2gltf
CLI tool to convert OBJ assets directly into GLTF and GLB formats.
- **Source:** [GitHub](https://github.com/CesiumGS/obj2gltf)
- **License:** Apache-2.0
- **Platform:** Node.js CLI

---

## Libraries & SDKs

### Three.js
Lightweight, high-level JavaScript 3D engine for WebGL.
- **Website:** [threejs.org](https://threejs.org/)
- **License:** MIT

### React Three Fiber (R3F)
React renderer for Three.js built for web and native interfaces.
- **Website:** [r3f.docs.pmnd.rs](https://r3f.docs.pmnd.rs/)
- **License:** MIT

### Babylon.js
Comprehensive web 3D engine for rendering, physics, and audio.
- **Website:** [babylonjs.com](https://www.babylonjs.com/)
- **License:** Apache-2.0

---

## Official Resources

- [Khronos gLTF 2.0 Specification](https://registry.khronos.org/glTF/specs/2.0/glTF-2.0.html)
- [Three.js Official Documentation](https://threejs.org/docs/)
- [Babylon.js Documentation](https://doc.babylonjs.com/)
- [Google model-viewer Documentation](https://modelviewer.dev/docs/)
- [Basis Universal GPU Texture Compression](https://github.com/BinomialLLC/basis_universal)

---

## Frequently Asked Questions

#### 1. How do I open a GLB file online without software installation?
You can upload any `.glb` or `.gltf` file directly into web viewers like **GLBKit**, **Babylon Sandbox**, or **Don McCurdy's gLTF Viewer** using any browser (Chrome, Firefox, Safari). No plugins or logins are required.

#### 2. What is the difference between GLB and gLTF formats?
`.gltf` is a text-based JSON file pointing to external binary (`.bin`) files and texture images. `.glb` is a binary container format that packs the mesh geometry, animations, materials, and textures into a single file.

#### 3. How can I inspect textures and materials inside a GLB file?
Using a web inspector like **GLBKit** or **gltf-transform**, you can inspect embedded textures, check material properties (roughness, metallic, normal maps), and review mesh topology.

#### 4. Which is the best free GLB Viewer for web developers?
**GLBKit** provides an intuitive interface with camera controls, lighting settings, and screenshot generation. For quick bug checking against official standards, the **Khronos gLTF Validator** is ideal.

#### 5. How do I validate a GLB file for structural errors?
Pass your model through the official **Khronos gLTF Validator**. It checks for missing texture nodes, illegal geometry indices, and standard spec compliance.

#### 6. How can I compress large GLB files for web deployment?
Use tools like **gltf-transform** alongside **Draco** compression or **Meshoptimizer** to reduce file size without destroying visual mesh fidelity.

#### 7. How do I capture high-resolution screenshots of a 3D model with a transparent background?
Use **GLBKit Screenshot Tool**, which allows you to adjust viewport resolution, frame the model, hide lighting, and export full PNG images with zero background color.

#### 8. Can Google Chrome open GLB files natively?
Chrome does not open 3D formats out of the box. You must load the file using a web viewer powered by WebGL/Three.js or integrate Google's `<model-viewer>` component into a page.

#### 9. Can I view GLB files on mobile devices (iOS / Android)?
Yes. WebGL-supported mobile browsers can open online viewers natively. Additionally, Android supports WebXR/SceneViewer and iOS supports QuickLook (via USDZ conversion).

#### 10. Can Blender export directly to GLB/gLTF?
Yes. Blender includes a native gLTF/GLB exporter under `File > Export > glTF 2.0 (.gltf/.glb)`.

#### 11. What is the difference between FBX and GLB?
FBX is a proprietary 3D format maintained by Autodesk primarily for desktop workflows. GLB is an open, WebGL-optimized standard tailored for fast network transmission and direct web rendering.

#### 12. How do I convert FBX to GLB?
You can convert FBX to GLB by importing the FBX into Blender and exporting it as gLTF 2.0, or by using automated conversion pipelines built on CLI tools.

#### 13. How do I convert GLB to USDZ for iOS AR applications?
You can use conversion tools like `google/model-viewer` CLI tools, Reality Converter on macOS, or `gltf-transform` plugins.

#### 14. What is Draco compression?
Draco is an open-source library developed by Google that drastically reduces the file size of 3D meshes and point clouds by compressing vertex buffers and indices.

#### 15. How do I optimize WebGL model performance?
Reduce draw calls by combining meshes, lower texture dimensions (use KTX2 / Basis Universal compression), reduce polygon counts, and remove unused animation channels.

---

## Made For

- **Three.js Developers**
- **React Three Fiber (R3F) Engineers**
- **WebGL / WebGPU Creators**
- **Unity & Godot Web Export Developers**
- **Blender & 3D Artists**
- **AR/VR & Spatial Computing Designers**

---

## Star & Contribute

If this repository helps your development workflow:
- ⭐ **Star the project** on GitHub
- 📢 **Share** with fellow web & 3D developers
- 💡 **Submit a Pull Request** to add new, high-quality GLB tools

---

## License

To the extent possible under law, the author(s) have waived all copyright and related or neighboring rights to this work under the **CC0 1.0 Universal (CC0 1.0) Public Domain Dedication**.
