# 🧪 Interactive 3D Periodic Table

![Tech Stack](https://img.shields.io/badge/Tech-HTML%20%7C%20CSS%20%7C%20Vanilla%20JS%20%7C%20Anime.js-cyan?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

A visually stunning, fully interactive 3D Periodic Table built using **Anime.js** and **CSS3D Transforms**. It brings chemistry to life with smooth spatial animations, sleek UI designs, and a suite of interactive tools to explore the atomic elements like never before!

---

## ✨ Features

- **🚀 3D Spatial Layouts:** Instantly transform the table into different geometric shapes with smooth Anime.js transitions. Available layouts:
  - `Table` (Standard periodic format)
  - `Sphere` (Orbital representation)
  - `Helix` (DNA-like structure)
  - `Grid` (Matrix layout)
  - `Shuffle 💥` (Scatters everything randomly into deep space)
  
- **🪐 Auto-Spin Mode:** Toggle the planetary spin on and let the entire structure rotate smoothly like a galaxy!

- **🔍 Smart Search & Highlight:** Looking for something specific?
  - Use the **Search Bar** to instantly highlight elements down by symbol or full name.
  - Use the **Category Filter** to isolate specific groups like _Alkali Metals_, _Noble Gases_, or _Actinides_.
  - Automatically dims unmatched elements in grayscale to let your targets shine!

- **📖 Deep Dive Stats:** Click on any element block to expand it and reveal:
  - Atomic Mass (u)
  - Density (g/cm³)
  - Melting & Boiling Points (°C)
  - **Wikipedia Integration:** Directly click "Wikipedia ↗" to instantly dive into the full lore of the element!

## 🛠️ Tech Stack

- **HTML5:** Semantic architecture.
- **CSS3:** Custom Variables (CSS Tokens), CSS3D Perspective, `transform-style: preserve-3d`.
- **JavaScript (ES6+):** Modular, structured state management.
- **Anime.js:** Highly sophisticated animation logic and dynamic layout creation.

## 🚀 How to Run Locally

Because the project leverages modern ES Module imports (`type="module"`), opening the HTML file directly through the `file://` protocol causes a CORS block. You must run a local web server!

1. Clone the repository:
   ```bash
   git clone https://github.com/subhadip758/periodic-table.git
   cd periodic-table
   ```
2. Start a local server. If you have Python installed, you can simply run:
   ```bash
   python -m http.server 8080
   ```
   Or if you prefer Node.js (`npx`):
   ```bash
   npx serve . -p 8080
   ```
3. Open your browser and go to `http://localhost:8080/`.

---

<p align="center">
  <b>Made with ❤️ by Subhadip</b>
</p>
