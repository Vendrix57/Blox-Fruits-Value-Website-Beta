# HardwareDealz Recommendations Clone 🖥️🔥

A sleek, responsive, frontend web interface designed to showcase optimized gaming PC configurations. It provides users with well-thought-out hardware component selections tailored to distinct pricing tiers, ensuring maximum price-to-performance ratios.

---

## 🌐 Live Preview Layout

The project consists of two core pages:
1. **Home / Landing Page (`main.html`):** Introduces the platform core philosophy, features an immersive background theme, interactive hero headers, and user experience rating components.
2. **PC Configurations Page (`Pc.html`):** Displays a structured grid matrix containing hardware tiers ranging from budget builds (€800) up to elite tier rigs featuring cutting-edge hardware (RTX 5090 / Ryzen 7800X3D).

---

## 🛠️ Tech Stack & Features

* **Semantic HTML5:** Clean architecture using standard document wrappers (`<div class="card">`, container structures, and micro-layouts).
* **Modern CSS3 styling:** * **Dynamic Grid Engine:** Layout uses standard `grid-template-columns: repeat(4, 1fr)` to adapt configurations beautifully into columns across standard displays.
  * **Glassmorphism Elements:** Subtle transparency using `rgba(0, 0, 0, 0.6)` combined with `backdrop-filter: blur(6px)` for high-contrast visibility against image backgrounds.
  * **Custom Animations:** Custom keyframes (`popIn` and `fadeIn`) that dynamically shift and fade card objects on screen load.
  * **UI Visual Enhancements:** Interactive scaling transformations (`transform: scale(1.03)`), radial glowing drop shadows (`drop-shadow`), and linear gradient typography text-clipping masks.

---

## 📁 File Structure

```text
├── main.html          # Main landing page interface
├── Pc.html            # Grid dashboard containing the hardware configurations
├── style.css          # Rulesets, layout specs, and core styles for main.html
├── PcStyle.css        # Responsive card design structures for Pc.html
└── img/               # Asset folder directory containing product builds and background files
    ├── LBGO0131.JPG   # Global background image asset
    ├── IMG_7681.PNG   # Global brand icon header
    └── ...            # Hardware component image files (.png / .webp)
