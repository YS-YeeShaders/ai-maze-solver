[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC_BY--NC--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

# 3D Evolutionary AI Maze Solver 🧠🌀

An interactive, browser-based 3D web application demonstrating parallel **Q-Learning** agents solving dynamically generated mazes. Features evolutionary selection cycles, adjustable high-speed physics simulation, and a retro Web 2.0 interface aesthetic.

---

## ✨ Features

- **Parallel Q-Learning Simulations:** 20 independent agents explore the same 20x20 maze concurrently in real time.
- **Evolutionary Selection:** Every 10 simulated seconds, the best-performing agent's Q-table matrix is cloned to all agents before generating a new solvable maze.
- **Interactive 3D Controls:** Full OrbitControls powered by **Three.js**—left-click and drag to rotate, scroll wheel to zoom.
- **High-Speed Simulation Control:** Adjustable FPS slider (1–1000 FPS) with instant preset fast-forward multipliers (1x, 5x, 10x, MAX).
- **Dynamic Path Visualization:** Select any individual agent's tab to view its active position, path trail, and step counter.
- **Classic Web 2.0 Aesthetics:** Styled with glossy bevels, metallic control panels, and retro tab layouts.

---

## 🚀 Live Demo

Check out the live interactive app here: **https://yeeshaders.github.io/ai-maze-solver/**

---

## 🛠️ How to Run Locally

Because this project is a standalone web application built with HTML, CSS, and Vanilla JavaScript, no installation or local server setup is required!

1. Clone or download this repository:
   ```bash
   git clone [https://github.com/YeeShaders/ai-maze-solver.git](https://github.com/YeeShaders/ai-maze-solver.git)
