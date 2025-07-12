# 3D Wireframe Engine (Assembly‑Style)

A retro‑themed, browser‑based **3D wireframe renderer** written in JavaScript, styled and documented like an x86 assembly program.  
It simulates CPU registers, memory segments and instruction listings while rendering dynamic 3D shapes on an HTML5 `<canvas>`.

---

## 🔍 Description

This project demonstrates low‑level concepts (registers, memory, instructions) in a modern web environment.  
You’ll see “MOV AX, 3D_ENGINE” next to a rotating cube, a live FPS counter, and interactive controls that feel like debugging in assembly.

---

## ⚙️ Features

- **Assembly‑Inspired UI**  
  - Simulated CPU _registers_ (AX, BX, CX, DX, SI, DI…)  
  - _Memory segments_ and _instruction list_ overlay  
- **Shapes**  
  - **Cube**, **Pyramid**, **Octahedron**  
- **Real‑Time Rendering**  
  - 60 FPS loop via `requestAnimationFrame`  
  - Perspective projection from 3D → 2D  
- **Interactive Controls**  
  - **WASD**: Rotate X/Y axes  
  - **Q/E**: Zoom In / Zoom Out  
  - **R/F**: Move Up / Move Down  
  - **Space**: Switch Shape  
  - **Esc**: Reset View  
  - **Mouse Drag** + **Wheel** support  
- **Live Stats**  
  - FPS, vertex & edge count, current rotation angle  

---

## 🚀 Live Demo

[View it in action »](https://your‑username.github.io/3d‑wireframe‑assembly/)

---

## 📁 Source Code

[github.com/your‑username/3d‑wireframe‑assembly](https://github.com/your‑username/3d‑wireframe‑assembly)

---

## 🛠 Installation & Usage

1. **Clone the repo**  
   ```bash
   git clone https://github.com/your‑username/3d‑wireframe‑assembly.git
   cd 3d‑wireframe‑assembly

2. **Open** `simple.html` in your browser (no build step required).
3. **Controls**:

   | Key         | Action                        |
   | ----------- | ----------------------------- |
   | **W/A/S/D** | Rotate around X/Y axes        |
   | **Q/E**     | Zoom In / Zoom Out            |
   | **R/F**     | Move Up / Move Down           |
   | **Space**   | Switch Shape                  |
   | **Esc**     | Reset View                    |
   | **Mouse**   | Drag to rotate, wheel to zoom |

---

## 📊 Technical Overview

* **File:** `simple.html` contains HTML, CSS & JS in one file.
* **Modules**

  * **Assembly UI:** DOM elements for registers, memory and instructions.
  * **Engine Core:**

    * **Vertices & Edges** arrays
    * **Matrix math** (`createRotationMatrix`, `multiplyMatrix`)
    * **Projection** (`project3D`)
    * **Render loop** (`mainLoop` → `requestAnimationFrame`)
  * **Input Handlers:** Keyboard & mouse listeners updating rotation/zoom.
* **Styling:** Monospaced “terminal” look with green-on-black theme and accent colors.

---

## 📈 Learning Goals

* Understand **3×3 rotation matrices** and **perspective projection**.
* See how an **event‑driven loop** manages real‑time rendering.
* Learn basic graphics algorithms (wireframe drawing, point projection).
* Appreciate low‑level concepts (registers, memory addresses) within high‑level JavaScript.

---

## 🚧 Future Enhancements

* **Shape Editor:** Live vertex editing “in memory.”
* **Performance Monitor:** Simulate stack pointer, memory usage stats.
* **WebGL Upgrade:** Migrate from Canvas2D to GPU shaders.
* **Assembly Emulator Mode:** Step through fake instructions.

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request for bug fixes, enhancements or new features.

---

## 📄 License

Distributed under the **MIT License**. See [LICENSE](LICENSE) for details.

```
```
