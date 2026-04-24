# 🌌 Gargantua Sim v2.5 - 3D Black Hole Visualization

An interactive, high-performance 3D scientific visualization of a supermassive black hole. This project uses **Three.js** and **WebGL** to simulate complex astrophysical phenomena in real-time, inspired by modern physics and the visual style of the movie *Interstellar*.

## ✨ Key Features

- **Accretion Disk:** A procedural system of **60,000 particles** simulating ionized gas. It features radial color grading (hot orange to deep red) and volumetric density.
- **Gravitational Lensing (Einstein Ring):** A simulated "Einstein Ring" that uses billboarding techniques to always face the camera, mimicking how light bends around a massive singularity.
- **Relativistic Jets:** Massive beams of blue plasma being ejected from the poles at near-light speeds, rendered with additive blending.
- **Event Horizon:** A perfectly dark central sphere representing the Schwarzschild radius where gravity is so strong that even light cannot escape.
- **Interactive Environment:** Smooth orbit controls and a dynamic starfield with 20,000 unique stars for a sense of scale.

## 🕹️ Controls

- **Rotate View:** Left Mouse Click + Drag
- **Zoom In/Out:** Mouse Scroll Wheel
- **Pan:** Right Mouse Click + Drag (or Shift + Left Click)

## 🛠️ Technical Breakdown

### Core Technologies
- **Three.js:** Used for the 3D scene graph, camera, and rendering.
- **BufferGeometry:** To maintain a high frame rate (60fps), all 60k particles are handled as high-performance buffer attributes.
- **Additive Blending:** Used for the accretion disk and jets to create a realistic "glow" effect where light overlaps.

### Physics Approximations
- **Disk Thinning:** The accretion disk is programmed to become thinner as the distance from the center increases ($y$ coordinate scaling).
- **Lensing Pulse:** The Einstein Ring has a subtle sine-wave pulsation to simulate the flickering of light near the photon sphere.

## 🚀 Deployment

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/black-hole-sim.git](https://github.com/YOUR_USERNAME/black-hole-sim.git)
   
2. Open index.html in any modern web browser.
3. GitHub Pages: This project is ready for one-click deployment. Go to Settings -> Pages and select the main branch.

📜 Credits

Inspired by the work of Kip Thorne and the VFX team at Double Negative. Built with ❤️ using the Three.js library.

Site is live at https://grujo85.github.io/black_hole_simulation/



