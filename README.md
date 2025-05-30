# 🌍 3JS Earth

A visually dynamic, interactive 3D representation of Earth rendered using **Three.js**. This project demonstrates realistic atmosphere, lighting, and starfield effects using custom shaders and materials.

## 🧠 Features

- 🌐 Realistic Earth sphere with Fresnel material effects
- ✨ Procedural starfield background
- 💡 Dynamic lighting to simulate sunlight
- 🎥 Smooth camera and scene setup with Three.js
- 📦 ES module import via CDN (`jsdelivr`)

## 🗂️ Project Structure

```bash
.
├── index.html           # Entry HTML file with import map and module loading
├── index.js             # Main JavaScript module: initializes scene, camera, renderer, and animation loop
├── getFresnelMat.js     # Function to create a Fresnel shader material for Earth
└── getStarfield.js      # Function to generate a starfield mesh
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (with module support)

### Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/bkandh30/3js-earth.git
   cd 3js-earth
   ```

2. Open `index.html` directly in your browser, or serve it using a simple local HTTP server:
   ```bash
   npx serve .
   ```

### CDN Dependencies

This project uses the following via [jsDelivr](https://www.jsdelivr.com/):

- [`three`](https://cdn.jsdelivr.net/npm/three@0.161/build/three.module.js)
- [`jsm/`](https://cdn.jsdelivr.net/npm/three@0.161/examples/jsm/)

## 🛠️ Built With

- [Three.js](https://threejs.org/) – JavaScript 3D library
- [ES Modules](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
