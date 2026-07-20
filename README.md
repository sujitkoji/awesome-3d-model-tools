# Awesome 3D Model Tools

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-blue.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GLB Viewer](https://img.shields.io/badge/GLB-Viewer-success)](https://glbkit.com)
[![Three.js Tools](https://img.shields.io/badge/Three.js-Tools-black)](https://threejs.org)
[![WebGL Developer](https://img.shields.io/badge/WebGL-Developer-blue)](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API)

> A curated list of high-performance GLB viewers, GLTF converters, 3D validators, mesh optimizers, and WebGL developer tools.

## Why This List?

Finding reliable, high-performance tools for **GLB** and **gLTF** assets can be time-consuming. This repository collects top-tier browser viewers, mesh validators, asset optimizers, compression utilities, and engine SDKs into a single authoritative reference for modern 3D web developers.

---

## Repository Stats

This repository is continuously updated to help developers discover the best tools, libraries, and resources for working with GLB, glTF, WebGL, and modern 3D workflows.

| Category | Count |
|-----------|------:|
| Browser Viewers | 10+ |
| Desktop Applications | 10+ |
| Screenshot Tools | 5+ |
| Validators & Analyzers | 8+ |
| Optimizers & Compression | 10+ |
| Converters & Editors | 10+ |
| Libraries & SDKs | 12+ |
| Official Resources | 15+ |
| Frequently Asked Questions | 20+ |

---

## Table of Contents

### Overview

- [Why This List?](#why-this-list)
- [Repository Stats](#repository-stats)
- [Recommended Tool](#recommended-tool)
- [Feature Comparison](#feature-comparison)

### Tools

- [Browser Viewers](#browser-viewers)
- [Desktop Viewers](#desktop-viewers)
- [Screenshot Tools](#screenshot-tools)
- [Validators & Analyzers](#validators--analyzers)
- [Optimizers & Compression](#optimizers--compression)
  - [Optimizers](#optimizers)
  - [Compression](#compression)
- [Converters & Editors](#converters--editors)
  - [Converters](#converters)
  - [Editors](#editors)
- [Libraries & SDKs](#libraries--sdks)

### Resources

- [Official Resources](#official-resources)
- [Learning Resources](#learning-resources)
- [Internal Resources](#internal-resources)
- [Frequently Asked Questions](#frequently-asked-questions)

### Community

- [Made For](#made-for)
- [Contributing](#contributing)
- [Support](#support)
- [License](#license)

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

### Don McCurdy glTF Viewer

Lightweight online glTF viewer built with Three.js for inspecting models, materials, animations, and lighting.

- **Website:** https://gltf-viewer.donmccurdy.com/
- **GitHub:** https://github.com/donmccurdy/three-gltf-viewer
- **License:** MIT
- **Platform:** Web
- **Best For:** Quick Preview, Debugging, Animation Testing

### Babylon.js Sandbox

Official browser-based viewer and playground from Babylon.js with built-in debugging tools.

- **Website:** https://sandbox.babylonjs.com/
- **GitHub:** https://github.com/BabylonJS/Babylon.js
- **License:** Apache-2.0
- **Platform:** Web
- **Best For:** Babylon.js Development, Material Testing, Scene Debugging

### Three.js Editor

Official online editor for creating, importing, and editing Three.js scenes.

- **Website:** https://threejs.org/editor/
- **GitHub:** https://github.com/mrdoob/three.js
- **License:** MIT
- **Platform:** Web
- **Best For:** Scene Editing, Three.js Development

### Google model-viewer

Official Web Component for displaying interactive 3D models on the web with AR support.

- **Website:** https://modelviewer.dev/
- **GitHub:** https://github.com/google/model-viewer
- **License:** Apache-2.0
- **Platform:** Web / Android / iOS
- **Best For:** Product Pages, E-commerce, AR Experiences

### PlayCanvas Viewer

Cloud-based WebGL viewer and editor powered by the PlayCanvas engine.

- **Website:** https://playcanvas.com/
- **GitHub:** https://github.com/playcanvas/engine
- **License:** MIT
- **Platform:** Web
- **Best For:** Interactive Web Apps, Games, Real-time Rendering

### Sketchfab

Popular online platform for publishing, viewing, sharing, and embedding interactive 3D models.

- **Website:** https://sketchfab.com/
- **GitHub:** https://github.com/sketchfab
- **License:** Proprietary
- **Platform:** Web
- **Best For:** Portfolio, Marketplace, 3D Showcase

### Vectary

Collaborative browser-based 3D design and visualization platform.

- **Website:** https://www.vectary.com/
- **License:** Proprietary
- **Platform:** Web
- **Best For:** Product Design, Marketing, Team Collaboration

### Verge3D

Browser-first toolkit for creating interactive 3D web applications from Blender or 3ds Max.

- **Website:** https://www.soft8soft.com/verge3d/
- **License:** Commercial
- **Platform:** Web
- **Best For:** Interactive Experiences, Product Configurators, Web Applications

## Desktop Viewers

Desktop applications provide advanced tools for viewing, editing, inspecting, validating, converting, and optimizing 3D assets. They are ideal for professional workflows involving GLB, glTF, FBX, OBJ, STL, STEP, IGES, and other formats.

### Blender

The industry-standard open-source 3D creation suite with comprehensive support for GLB, glTF, FBX, OBJ, STL, USD, and many other formats.

- **Website:** https://www.blender.org/
- **GitHub:** https://github.com/blender/blender
- **License:** GPL-3.0
- **Platform:** Windows, macOS, Linux
- **Best For:** Modeling, Animation, Rendering, Exporting, Game Assets

### Gestaltor

Professional desktop editor built specifically for editing, validating, and optimizing glTF and GLB assets.

- **Website:** https://gestaltor.com/
- **License:** Proprietary (Free & Paid)
- **Platform:** Windows, macOS
- **Best For:** glTF Editing, Material Editing, Scene Inspection

### MeshLab

Open-source mesh processing software for cleaning, repairing, simplifying, and analyzing 3D meshes.

- **Website:** https://www.meshlab.net/
- **GitHub:** https://github.com/cnr-isti-vclab/meshlab
- **License:** GPL-3.0
- **Platform:** Windows, macOS, Linux
- **Best For:** Mesh Repair, Simplification, Point Clouds, Inspection

### FreeCAD

Open-source parametric CAD software supporting engineering and manufacturing workflows with import/export for multiple 3D formats.

- **Website:** https://www.freecad.org/
- **GitHub:** https://github.com/FreeCAD/FreeCAD
- **License:** LGPL-2.1
- **Platform:** Windows, macOS, Linux
- **Best For:** CAD Design, Engineering Models, STEP & IGES Files

### Autodesk Fusion

Professional CAD, CAM, and product design platform with extensive support for engineering and manufacturing workflows.

- **Website:** https://www.autodesk.com/products/fusion-360/
- **License:** Proprietary
- **Platform:** Windows, macOS
- **Best For:** Product Design, CAD Modeling, Manufacturing

### Windows 3D Viewer

Microsoft's built-in desktop application for viewing, rotating, and inspecting common 3D model formats.

- **Website:** https://apps.microsoft.com/
- **License:** Proprietary
- **Platform:** Windows
- **Best For:** Quick Preview, Basic Inspection, Windows Users

### Autodesk FBX Review

Lightweight desktop viewer for reviewing FBX animations and 3D assets without opening a full 3D editor.

- **Website:** https://www.autodesk.com/products/fbx/fbx-review
- **License:** Free
- **Platform:** Windows
- **Best For:** FBX Review, Animation Playback, Asset Validation

### Open 3D Engine (O3DE)

Open-source real-time 3D engine for building games, simulations, and interactive experiences.

- **Website:** https://o3de.org/
- **GitHub:** https://github.com/o3de/o3de
- **License:** Apache-2.0
- **Platform:** Windows, Linux
- **Best For:** Real-Time Rendering, Simulation, Game Development

### Unity

Industry-leading game engine with robust support for importing GLB, glTF (via plugins), FBX, OBJ, and other 3D assets.

- **Website:** https://unity.com/
- **License:** Proprietary
- **Platform:** Windows, macOS
- **Best For:** Game Development, AR, VR, Mobile Apps

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

Validators and analyzers help ensure that GLB and glTF files follow the official specification, detect structural issues, identify compatibility problems, and improve asset quality before deployment.

---

### Khronos glTF Validator

The official validator maintained by the Khronos Group for verifying glTF 2.0 compliance and detecting specification errors.

- **Website:** https://github.com/KhronosGroup/glTF-Validator
- **License:** Apache-2.0
- **Platform:** Web, CLI, Node.js
- **Best For:** Specification Validation, Error Detection, CI/CD Integration

### glTF Transform Inspect

Powerful inspection tool included with glTF Transform for analyzing model statistics, geometry, textures, materials, animations, and optimization opportunities.

- **Website:** https://gltf-transform.dev/
- **GitHub:** https://github.com/donmccurdy/glTF-Transform
- **License:** MIT
- **Platform:** CLI, Node.js
- **Best For:** Model Analysis, Asset Inspection, Optimization Reports

### glTF Report

Interactive web-based analyzer that generates detailed reports for glTF and GLB assets, including mesh statistics, texture information, materials, animations, and rendering performance.

- **Website:** https://gltf.report/
- **GitHub:** https://github.com/ux3d/gltf-report
- **License:** MIT
- **Platform:** Web
- **Best For:** Performance Analysis, Asset Reports, Model Statistics

### Gestaltor Validation

Built-in validation tools for inspecting glTF and GLB assets, identifying issues, and verifying compatibility before publishing.

- **Website:** https://gestaltor.com/
- **License:** Proprietary
- **Platform:** Windows, macOS
- **Best For:** Professional Validation, Asset Editing, Production Workflows

### Babylon.js Inspector

Built-in scene inspector for debugging meshes, materials, textures, cameras, lights, and rendering performance in Babylon.js applications.

- **Website:** https://doc.babylonjs.com/
- **GitHub:** https://github.com/BabylonJS/Babylon.js
- **License:** Apache-2.0
- **Platform:** Web
- **Best For:** Scene Debugging, Material Inspection, Performance Analysis

### Three.js Inspector Tools

Developer tools and debugging utilities for inspecting Three.js scenes, meshes, materials, textures, cameras, and rendering performance.

- **Website:** https://threejs.org/
- **GitHub:** https://github.com/mrdoob/three.js
- **License:** MIT
- **Platform:** Web
- **Best For:** Three.js Debugging, Scene Inspection, Performance Profiling

---

## Optimizers & Compression

Optimization and compression tools help reduce file size, improve loading speed, lower memory usage, and increase rendering performance for GLB and glTF assets.

## Optimizers

### glTF Transform

Powerful toolkit for inspecting, editing, optimizing, and transforming glTF and GLB assets.

- **Website:** https://gltf-transform.dev/
- **GitHub:** https://github.com/donmccurdy/glTF-Transform
- **License:** MIT
- **Platform:** CLI, Node.js
- **Best For:** Optimization, Asset Processing, Batch Workflows

### Meshoptimizer

Industry-standard mesh optimization library designed to improve rendering performance and compression efficiency.

- **Website:** https://meshoptimizer.org/
- **GitHub:** https://github.com/zeux/meshoptimizer
- **License:** MIT
- **Platform:** C++, JavaScript, WASM
- **Best For:** Vertex Optimization, LOD Generation, Runtime Performance

### gltfpack

High-performance glTF optimizer built on top of Meshoptimizer.

- **Website:** https://meshoptimizer.org/gltf/
- **GitHub:** https://github.com/zeux/meshoptimizer
- **License:** MIT
- **Platform:** CLI
- **Best For:** File Size Reduction, Production Deployment

### Blender Optimization Tools

Built-in tools for mesh cleanup, decimation, texture optimization, and export preparation.

- **Website:** https://www.blender.org/
- **License:** GPL-3.0
- **Platform:** Windows, macOS, Linux
- **Best For:** Manual Optimization, Asset Cleanup

---

## Compression

### Draco

Open-source geometry compression library developed by Google for reducing mesh and point cloud file sizes.

- **Website:** https://google.github.io/draco/
- **GitHub:** https://github.com/google/draco
- **License:** Apache-2.0
- **Platform:** C++, JavaScript, WASM
- **Best For:** Geometry Compression, Smaller Downloads

### Meshoptimizer Compression

Compression algorithms for index buffers, vertex buffers, and mesh data.

- **Website:** https://meshoptimizer.org/
- **GitHub:** https://github.com/zeux/meshoptimizer
- **License:** MIT
- **Platform:** C++, JavaScript, WASM
- **Best For:** Runtime Performance, Efficient Asset Delivery

### Basis Universal

Universal texture compression system designed for efficient GPU texture delivery across multiple platforms.

- **Website:** https://github.com/BinomialLLC/basis_universal
- **GitHub:** https://github.com/BinomialLLC/basis_universal
- **License:** Apache-2.0
- **Platform:** C++, JavaScript
- **Best For:** Texture Compression, Cross-Platform Rendering

### KTX2

Modern container format for GPU-compressed textures used in WebGL, WebGPU, Three.js, and Babylon.js workflows.

- **Website:** https://www.khronos.org/ktx/
- **GitHub:** https://github.com/KhronosGroup/KTX-Software
- **License:** Apache-2.0
- **Platform:** Cross Platform
- **Best For:** GPU Textures, Fast Loading, Reduced Memory Usage

### BasisU + KTX2 Workflow

Recommended modern texture pipeline for web-based 3D applications.

Benefits:

- Smaller Texture Files
- Faster Downloads
- Reduced GPU Memory Usage
- Better Mobile Performance
- Three.js Compatible
- Babylon.js Compatible
- WebGPU Ready

### Recommended Stack

For production-ready GLB and glTF assets:

- **glTF Transform** → Asset Processing
- **Meshoptimizer** → Geometry Optimization
- **Draco** → Mesh Compression
- **Basis Universal** → Texture Compression
- **KTX2** → GPU Texture Delivery

This combination provides the best balance between file size, loading speed, visual quality, and runtime performance.

---

## Converters & Editors

Converting and editing tools help developers transform 3D assets between different file formats while preserving geometry, materials, textures, animations, and scene hierarchy.

## Converters

### obj2gltf

Command-line tool for converting OBJ models into glTF and GLB formats.

- **Website:** https://github.com/CesiumGS/obj2gltf
- **GitHub:** https://github.com/CesiumGS/obj2gltf
- **License:** Apache-2.0
- **Platform:** Node.js CLI
- **Best For:** OBJ to glTF / GLB Conversion

### FBX2glTF

Official converter for transforming Autodesk FBX files into glTF and GLB.

- **Website:** https://github.com/facebookincubator/FBX2glTF
- **GitHub:** https://github.com/facebookincubator/FBX2glTF
- **License:** BSD-3-Clause
- **Platform:** Windows, macOS, Linux
- **Best For:** FBX to glTF Conversion

### Blender

Open-source 3D suite capable of importing and exporting GLB, glTF, FBX, OBJ, STL, USD, and many other formats.

- **Website:** https://www.blender.org/
- **GitHub:** https://github.com/blender/blender
- **License:** GPL-3.0
- **Platform:** Windows, macOS, Linux
- **Best For:** Universal 3D Format Conversion

### CAD Exchanger

Professional software for converting CAD and 3D formats including STEP, IGES, JT, FBX, OBJ, STL, and glTF.

- **Website:** https://cadexchanger.com/
- **License:** Commercial
- **Platform:** Windows, macOS, Linux
- **Best For:** CAD & Engineering Format Conversion

---

## Editors

### Gestaltor

Professional editor designed specifically for glTF and GLB assets with validation and material editing.

- **Website:** https://gestaltor.com/
- **License:** Proprietary
- **Platform:** Windows, macOS
- **Best For:** glTF Editing, Material Editing

### Three.js Editor

Official browser-based editor for creating, importing, and editing Three.js scenes.

- **Website:** https://threejs.org/editor/
- **GitHub:** https://github.com/mrdoob/three.js
- **License:** MIT
- **Platform:** Web
- **Best For:** Scene Editing, Three.js Development

### PlayCanvas Editor

Cloud-based visual editor for building interactive WebGL experiences and games.

- **Website:** https://playcanvas.com/editor
- **GitHub:** https://github.com/playcanvas/engine
- **License:** MIT
- **Platform:** Web
- **Best For:** Interactive 3D Applications
  
---

## Libraries & SDKs

Libraries and SDKs provide the foundation for building modern 3D web applications, game experiences, product configurators, AR/VR interfaces, and interactive WebGL content.

### Three.js

The most popular JavaScript 3D library for building interactive WebGL experiences in the browser.

- **Website:** https://threejs.org/
- **GitHub:** https://github.com/mrdoob/three.js
- **License:** MIT
- **Platform:** Web
- **Best For:** WebGL Applications, Interactive 3D, Visualization

### React Three Fiber (R3F)

A React renderer for Three.js that enables declarative 3D development using React components.

- **Website:** https://r3f.docs.pmnd.rs/
- **GitHub:** https://github.com/pmndrs/react-three-fiber
- **License:** MIT
- **Platform:** React
- **Best For:** React Applications, Interactive UI, Modern Web Apps

### Drei

A collection of useful helpers, abstractions, and ready-to-use components for React Three Fiber.

- **Website:** https://github.com/pmndrs/drei
- **GitHub:** https://github.com/pmndrs/drei
- **License:** MIT
- **Platform:** React
- **Best For:** Cameras, Controls, Loaders, Helpers, Effects

### Three Stdlib

Community-maintained utilities extracted from Three.js examples for modern JavaScript projects.

- **Website:** https://github.com/pmndrs/three-stdlib
- **GitHub:** https://github.com/pmndrs/three-stdlib
- **License:** MIT
- **Platform:** JavaScript
- **Best For:** Controls, Loaders, Postprocessing Utilities

### Babylon.js

A complete open-source 3D engine for building games, simulations, visualization tools, and WebXR experiences.

- **Website:** https://www.babylonjs.com/
- **GitHub:** https://github.com/BabylonJS/Babylon.js
- **License:** Apache-2.0
- **Platform:** Web
- **Best For:** Games, Simulations, AR/VR, Product Configurators

### glTF Transform

Powerful SDK and CLI for editing, validating, optimizing, compressing, and converting glTF and GLB assets.

- **Website:** https://gltf-transform.dev/
- **GitHub:** https://github.com/donmccurdy/glTF-Transform
- **License:** MIT
- **Platform:** Node.js
- **Best For:** Optimization, Compression, Asset Pipelines

### GLTFLoader

Official Three.js loader for importing GLB and glTF models into WebGL applications.

- **Website:** https://threejs.org/docs/
- **GitHub:** https://github.com/mrdoob/three.js
- **License:** MIT
- **Platform:** JavaScript
- **Best For:** Loading GLB & glTF Assets

### DRACOLoader

Official Three.js loader for decoding Draco-compressed geometry.

- **Website:** https://threejs.org/docs/
- **GitHub:** https://github.com/mrdoob/three.js
- **License:** MIT
- **Platform:** JavaScript
- **Best For:** Draco Mesh Compression

### KTX2Loader

Official Three.js loader for loading KTX2/Basis Universal compressed GPU textures.

- **Website:** https://threejs.org/docs/
- **GitHub:** https://github.com/mrdoob/three.js
- **License:** MIT
- **Platform:** JavaScript
- **Best For:** GPU Texture Compression

### MeshoptDecoder

Official decoder for Meshoptimizer-compressed geometry used in glTF assets.

- **Website:** https://github.com/zeux/meshoptimizer
- **GitHub:** https://github.com/zeux/meshoptimizer
- **License:** MIT
- **Platform:** JavaScript / WASM
- **Best For:** Fast Geometry Decoding

### @gltf-transform/functions

Collection of reusable optimization, transformation, and compression utilities built on top of glTF Transform.

- **Website:** https://gltf-transform.dev/
- **GitHub:** https://github.com/donmccurdy/glTF-Transform
- **License:** MIT
- **Platform:** Node.js
- **Best For:** Asset Automation

### @gltf-transform/extensions

Utilities for working with official Khronos glTF extensions.

- **Website:** https://gltf-transform.dev/
- **GitHub:** https://github.com/donmccurdy/glTF-Transform
- **License:** MIT
- **Platform:** Node.js
- **Best For:** glTF Extensions

---

## Official Resources

Official documentation, specifications, APIs, SDKs, and standards for modern 3D graphics, WebGL, WebGPU, and glTF development.

### Khronos Group

The official organization behind the glTF 2.0 specification, Vulkan, OpenXR, OpenCL, and OpenGL standards.

- **Website:** https://www.khronos.org/
- **Best For:** glTF Specification, Open Standards, APIs

### glTF 2.0 Specification

Official specification for the glTF 2.0 file format.

- **Website:** https://registry.khronos.org/glTF/specs/2.0/glTF-2.0.html
- **Maintained By:** Khronos Group

### Three.js Documentation

Official documentation for the Three.js JavaScript 3D library.

- **Website:** https://threejs.org/docs/
- **Examples:** https://threejs.org/examples/

### Babylon.js Documentation

Official documentation for Babylon.js.

- **Website:** https://doc.babylonjs.com/

### React Three Fiber (R3F)

Official documentation for React Three Fiber.

- **Website:** https://r3f.docs.pmnd.rs/

### Drei

Official documentation for Drei.

- **Website:** https://github.com/pmndrs/drei

### OpenUSD

Universal Scene Description (USD) framework developed by Pixar for interoperable 3D scenes.

- **Website:** https://openusd.org/
- **Best For:** Film, VFX, CAD, Interchange

### OpenXR

Cross-platform API standard for augmented reality (AR), virtual reality (VR), and mixed reality (MR).

- **Website:** https://www.khronos.org/openxr/

### WebGPU

The next-generation graphics API for the modern web.

- **Website:** https://gpuweb.github.io/gpuweb/
- **Best For:** High-performance graphics and compute

### Draco Compression

Google's open-source geometry compression library for reducing GLB and glTF mesh sizes.

- **Website:** https://google.github.io/draco/
- **GitHub:** https://github.com/google/draco

### Meshoptimizer

High-performance mesh optimization library for rendering and compression.

- **Website:** https://meshoptimizer.org/
- **GitHub:** https://github.com/zeux/meshoptimizer

### Basis Universal

Universal GPU texture compression system used by KTX2 textures.

- **Website:** https://github.com/BinomialLLC/basis_universal
- **Best For:** GPU Texture Compression

### KTX2

Official Khronos texture container format optimized for GPU-compressed textures.

- **Website:** https://www.khronos.org/ktx/
- **Specification:** https://registry.khronos.org/KTX/

### WebGL

Official documentation and guides for the WebGL API.

- **Website:** https://developer.mozilla.org/docs/Web/API/WebGL_API

### WebGL Fundamentals

One of the best educational resources for learning WebGL.

- **Website:** https://webglfundamentals.org/

### WebGPU Fundamentals

Hands-on tutorials for learning WebGPU.

- **Website:** https://webgpufundamentals.org/

### ShaderToy

Interactive platform for creating and sharing GLSL shaders.

- **Website:** https://www.shadertoy.com/

### Blender Documentation

Official Blender manual and API documentation.

- **Website:** https://docs.blender.org/

### model-viewer Documentation

Official documentation for Google's `<model-viewer>` web component.

- **Website:** https://modelviewer.dev/docs/

---

## Learning Resources

The following learning resources help developers master GLB, glTF, WebGL, Three.js, React Three Fiber, shaders, and modern 3D graphics development.

### Books

- **WebGL Programming Guide**
- **Real-Time Rendering**
- **Physically Based Rendering**
- **Game Engine Architecture**

### Courses

- Three.js Journey
- React Three Fiber Courses
- Blender Fundamentals
- WebGL Fundamentals

### Tutorials

- Three.js Tutorials
- React Three Fiber Tutorials
- Babylon.js Tutorials
- Blender Tutorials
- glTF Tutorials

### Videos

- Three.js YouTube Tutorials
- React Three Fiber Videos
- Blender Beginner Guides
- WebGL Development Videos
- Shader Programming Videos

### GLSL & Shaders

- ShaderToy
- The Book of Shaders
- GLSL References
- Noise Functions
- Signed Distance Functions (SDF)

### WebGPU

- WebGPU Fundamentals
- WebGPU Specification
- WGSL Documentation
- GPUWeb Resources

---

## Internal Resources

Learn more about working with GLB and glTF files through step-by-step guides and tutorials.

### Guides

- **How to Use GLB Viewer**
  - https://www.glbkit.com/guides/how-to-use-glb-viewer

- **How to Take GLB Screenshots**
  - https://www.glbkit.com/guides/how-to-take-glb-screenshots

### Tools

- **GLB Viewer**
  - https://www.glbkit.com/glb-viewer

- **GLB Screenshot Tool**
  - https://www.glbkit.com/glb-screenshot

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

## Contributing

Contributions are welcome and greatly appreciated.

You can help improve this repository by:

- Adding high-quality 3D tools
- Adding GLB and glTF utilities
- Improving descriptions
- Fixing broken links
- Updating outdated resources
- Improving documentation
- Suggesting new categories
- Reporting issues

Before submitting a Pull Request, please ensure that:

- The tool is actively maintained.
- The description is clear and concise.
- Official documentation is preferred.
- Duplicate entries are avoided.
- Links are valid and working.

Please read the **CONTRIBUTING.md** guide before opening a Pull Request.

Thank you for helping make this repository a valuable resource for the 3D developer community.

--- 

## Support

If you find this repository useful:

- ⭐ Star this repository
- 🍴 Fork it
- 📢 Share it with other developers
- 💡 Submit new tools and resources

Every contribution helps make this collection better for the entire 3D community.

---

Made with ❤️ for the Three.js, React Three Fiber, Babylon.js, WebGL, WebGPU, and glTF communities.

## License

This work is dedicated to the public domain under the **Creative Commons CC0 1.0 Universal (CC0 1.0) Public Domain Dedication**.

To the extent possible under law, the author(s) have waived all copyright and related or neighboring rights to this repository.

For the full license text, see the [LICENSE](LICENSE) file or visit:

https://creativecommons.org/publicdomain/zero/1.0/

---
