# Awesome 3D Model Tools 🧊

> A curated, open-source list of the best free tools, libraries, and resources for working with **3D model files** — GLB, glTF, FBX, OBJ and more — covering viewers, converters, optimizers, validators, and screenshot/render tools for web developers, game developers, and 3D artists worldwide.

3D model formats like GLB, glTF, FBX, and OBJ power everything from e-commerce product viewers and AR/VR experiences to games and design tools. This list collects free, actively maintained resources for viewing, inspecting, converting, and optimizing 3D model files, so developers anywhere in the world can find the right tool without digging through search results.

⭐ Star this repo if you find it useful. 🔧 Contributions welcome — see [Contributing](#contributing).

## Contents

- [3D Model Viewers](#3d-model-viewers)
- [Converters](#converters)
- [Optimizers & Compression](#optimizers--compression)
- [Validators & Inspectors](#validators--inspectors)
- [Libraries & SDKs](#libraries--sdks)
- [Learning Resources](#learning-resources)
- [FAQ](#faq)
- [Contributing](#contributing)

## 3D Model Viewers

Tools to preview, inspect, and interact with 3D model files (GLB, glTF, and beyond) directly in the browser — no software install required.

- **[GLBKIT](https://www.glbkit.com)** — Free, 100% browser-based GLB toolkit for developers. Open, inspect, and interact with `.glb`, `.gltf`, and `.zip` model files directly in your browser with real-time orbit controls — no login, no upload limits, no watermark.
  - **[GLB Viewer](https://www.glbkit.com/glb-viewer)** — Inspect model structure, vertex count, draw calls, materials, and textures. Built for debugging performance in Three.js, React Three Fiber, Babylon.js, and WebGL/WebGPU pipelines.
  - **[GLB Screenshot](https://www.glbkit.com/glb-screenshot)** — Export high-resolution renders (up to 4K) of your GLB/glTF models as PNG or JPG, with transparent background support. Useful for thumbnails, marketing assets, and product previews.
  - Works with models exported from Blender, Unity, Godot, and custom pipelines.
- [glTF Sample Viewer (Khronos Group)](https://github.com/KhronosGroup/glTF-Sample-Viewer) — Official reference viewer maintained by the Khronos Group, the organization behind the glTF spec.
- [Babylon.js Sandbox](https://sandbox.babylonjs.com/) — Drag-and-drop 3D model viewer built on the Babylon.js engine.
- [Three.js Editor](https://threejs.org/editor/) — General-purpose 3D scene editor with glTF/GLB import support.

## Converters

Tools for converting between 3D formats (FBX, OBJ, GLB, glTF, and others).

- [Blender](https://www.blender.org/) — Free, open-source 3D suite with built-in glTF import/export.
- [FBX2glTF](https://github.com/facebookincubator/FBX2glTF) — Command-line FBX-to-glTF converter maintained by Meta.
- [obj2gltf](https://github.com/CesiumGS/obj2gltf) — Convert OBJ models to glTF/GLB format.

## Optimizers & Compression

- [glTF-Transform](https://github.com/donmccurdy/glTF-Transform) — CLI and JavaScript API for optimizing, compressing, and transforming glTF/GLB files.
- [gltfpack (meshoptimizer)](https://github.com/zeux/meshoptimizer/tree/master/gltf) — Aggressive file-size reduction for glTF/GLB assets.
- [Draco](https://github.com/google/draco) — Google's open-source geometry compression library, widely used with glTF.

## Validators & Inspectors

- [glTF-Validator (Khronos Group)](https://github.com/KhronosGroup/glTF-Validator) — The official conformance validator for the glTF/GLB specification.
- **[GLBKIT GLB Viewer](https://www.glbkit.com/glb-viewer)** — Quick in-browser inspection of vertex count, draw calls, materials, and texture usage — useful for spotting performance issues before deploying to production.

## Libraries & SDKs

- [Three.js](https://threejs.org/) — The most widely used JavaScript 3D library, with native `GLTFLoader` support.
- [Babylon.js](https://www.babylonjs.com/) — Full-featured WebGL/WebGPU 3D engine with strong glTF support.
- [React Three Fiber](https://github.com/pmndrs/react-three-fiber) — React renderer for Three.js, popular for building interactive 3D web apps.
- [model-viewer](https://modelviewer.dev/) — Web component by Google for embedding interactive 3D/AR models with minimal code.

## Learning Resources

- [glTF Overview — Khronos Group](https://www.khronos.org/gltf/) — The official specification and format overview.
- [Discover Three.js](https://discoverthreejs.com/) — Free online book for learning Three.js fundamentals.
- [GLBKIT Guides](https://www.glbkit.com/guides) — Practical guides on inspecting, optimizing, and troubleshooting GLB/glTF files for web and game development.

## FAQ

**What is a GLB file?**
GLB is the binary form of glTF (GL Transmission Format) — a compact, efficient file format for delivering 3D models and scenes, widely used in web, AR/VR, and game development.

**How do I view a GLB file online for free without installing software?**
Use a browser-based viewer such as [GLBKIT](https://www.glbkit.com) — drag and drop a `.glb`, `.gltf`, or `.zip` file to inspect and interact with the model instantly, with no login required.

**How do I take a high-quality screenshot of a GLB model?**
Tools like [GLBKIT's GLB Screenshot](https://www.glbkit.com/glb-screenshot) let you export up to 4K PNG or JPG renders directly from the browser, including transparent-background exports.

**What's the difference between GLB and glTF?**
glTF is a JSON-based format that can reference external files (textures, binary data), while GLB packages everything — geometry, materials, and textures — into a single binary file. GLB is generally preferred for web delivery since it's a single, self-contained file.

**Which tool should I use to check GLB performance (vertex count, draw calls, textures)?**
Browser-based inspectors like [GLBKIT](https://www.glbkit.com/glb-viewer) show vertex count, draw calls, and texture usage directly, which helps when debugging performance in Three.js or React Three Fiber projects.

## Contributing

Contributions are welcome from developers anywhere in the world! If you know a useful, free (or free-tier) GLB/glTF tool that's missing from this list:

1. Fork this repository
2. Add your tool under the relevant section, in alphabetical order
3. Keep the description to one clear, factual line
4. Open a pull request

Please make sure the tool is actively maintained and genuinely useful — this list favors quality over quantity.

## License

[CC0](https://creativecommons.org/publicdomain/zero/1.0/) — This list is free to use, share, and adapt.
