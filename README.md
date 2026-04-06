# 🌌 3D Live Solar System - Octos Wallpaper

An astronomically accurate, high-fidelity 3D Solar System live wallpaper built with Three.js. This wallpaper is fully interactive and optimized for the **Octos** dynamic desktop engine.

## ✨ Features

- **Astronomically Accurate**: Planets are positioned in real-time based on the J2000 epoch and synced to **Indian Standard Time (IST)**.
- **Scientific Orbital Mechanics**: 
  - **Elliptical Orbits**: Planets follow their true eccentricity ($e$) with the Sun at one focus.
  - **Axial Tilt**: Each planet (including Earth at 23.4° and Uranus at 97.7°) rotates on its correct axis.
  - **Inclination**: Orbits are tilted relative to each other for a realistic, non-concentric view.
- **High Fidelity**: 
  - Optimized for **8K textures**.
  - Physically-based rendering (PBR) with ACES Filmic tone mapping.
  - Interactive 3D controls (OrbitControls).
- **Octos Integrated**: Fully compatible with the [Octos Desktop Engine](https://github.com/underpig1/octos).

## 🚀 Getting Started

### 1. Download Textures
Due to their size, 8K textures are not included in this repository. 
1. Visit [Solar System Scope Textures](https://www.solarsystemscope.com/textures/).
2. Download the **8K** versions of all planets, the Sun, and the stars.
3. Place them in a folder named `textures/` in the root directory.
4. Ensure they follow the naming convention: `8k_earth_daymap.jpg`, `8k_sun.jpg`, etc. (See `ASSETS` in `solar_system.html`).

### 2. Setting as Live Wallpaper (via Octos)
1. Install [Octos](https://github.com/underpig1/octos) from the Microsoft Store or GitHub.
2. Open Octos and click on **Add Wallpaper**.
3. Select the `solar_system.html` file from this project.
4. Enjoy your live, interactive 3D solar system!

## 🛠 Tech Stack
- **Three.js**: 3D Rendering engine.
- **JavaScript (ES6)**: Real-time orbital calculations.
- **CSS3**: Glassmorphism UI overlay.
- **Octos API**: For seamless desktop integration.

## 🤝 Contributing
This project is open-source! Feel free to:
- Open issues for astronomical corrections.
- Submit PRs for new features (e.g., more moons, asteroid belts).
- Port it to other wallpaper engines.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
