# 🧪 Interactive 3D Periodic Table & Educational Sandbox

![Tech Stack](https://img.shields.io/badge/Tech-HTML%20%7C%20CSS%20%7C%20Vanilla%20JS%20%7C%20Anime.js-cyan?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

A visually stunning, fully interactive 3D Periodic Table built originally around **Anime.js** and **CSS3D Transforms** that has been heavily evolved into a fully-fledged **educational sandbox game**. It visually brings atomic physics and chemistry logic to life with spatial animations, immersive learning modes, and real-time simulations.

![Application Showcase](./preview.png)

---

## 🎮 The Three Game Modes

The application features three distinct interconnected gameplay modes, dynamically toggled via the bottom navigation bar:

### 1. 🔍 EXPLORE MODE (The 3D Atlas)
The foundational mode. Freely explore the beautiful 3D map of the elements with unprecedented detail.
- **Advanced Trend Heatmaps**: Select a periodic trend (e.g., _Ionization Energy, Atomic Radius, Electronegativity_) from the dropdown. The entire table flashes into a beautiful gradient heatmap, explicitly dropping dynamically generated trend vector arrows to strictly map out the structural increases and decreases.
- **Interactive State of Matter (Phases) Simulator**: Drag the **Env Temp** slider between `0K` and `6000K`. The framework actively calculates the ambient temperature against every element's boiling and melting points! Watch solids melt into deep blue liquids or vaporize into green gases across your screen based on actual known thermodynamic data!
- **Deep Dive Elements Panel**: Click any element to dive into its properties.
   - **Physics & Chemistry Exceptions**: The data engine explicitly warns students about any famous atomic exceptions (like *Chromium's weird d-orbital filling* or *Nitrogen's half-shell ionizing stability*).
   - **3D Bohr Atom Viewer**: Inside the panel, hit the `View 3D Atom Model` button. The engine parses the atomic electron config, computes Bohr shell counts (K, L, M), and renders an independent, spinning 3D CSS model populated with the mathematically accurate count of electrons!

### 2. 🧪 BUILDER MODE (The Reaction Crucible)
A gamified Sandbox meant to test chemical interactions.
- Switching to `BUILDER` drops down the **Reaction Crucible**.
- Click any two elements on the table to drop them into the Crucible (`Na` + `Cl`).
- Hit **REACT**! The engine intercepts their true Pauling Electronegativity data, calculates the difference (∆EN), and predicts the bond physics—teaching you instantly if it forms an **Ionic Bond ⚡**, **Polar Covalent Bond 💧**, or **Nonpolar Covalent Bond 🤝**.

### 3. 🎯 QUIZ MODE (Teacher's Test)
A thrilling memorization HUD.
- Clicking `QUIZ` strips every single identifying text, symbol, and atomic number off the 3D table, leaving only raw, mysteriously colored blocks floating in space.
- The HUD flashes a prompt: *"Find the Element: Titanium"*.
- The student must hunt and click the exact cube on the grid. Guessing hits are rewarded with green flashes and points, while misses flash a punishing red.

---

## ✨ Foundational Core Features

- **🚀 3D Spatial Layouts:** Instantly transform the table into different geometric shapes with smooth Anime.js transitions. Available layouts:
  - `Table` (Standard periodic format)
  - `Sphere` (Orbital representation)
  - `Helix` (DNA-like structure)
  - `Grid` (Matrix layout)
  - `Shuffle 💥` (Scatters everything randomly into deep space)
  
- **🪐 Auto-Spin Mode:** Toggle the planetary spin on and let the entire spatial structure rotate smoothly.

- **🔍 Smart Search & Highlight:** Looking for something specific?
  - Use the **Search Bar** to instantly highlight elements down by symbol or full name.
  - Use the **Category Filter** to isolate specific groups. *When selecting a group (like Halogens), an elegant banner drops down teaching you what that group actually represents in chemistry.*

## 🛠️ Tech Stack

- **HTML5:** Semantic architecture.
- **CSS3:** Extremely complex CSS Variables, CSS3D Perspectives, and custom keyframes.
- **JavaScript (ES6+):** Pure vanilla modular JS. Dynamic DOM manipulation for the sandbox UI. No heavy framework (React/Vue) dependencies required!
- **Anime.js:** Highly sophisticated animation logic and spatial geometry manipulation.

## 🚀 How to Run Locally

Because the project leverages modern ES Module imports (`type="module"`), opening the HTML file directly through the `file://` protocol effectively causes a CORS block. You must run a local web server!

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
  <b>Built to make learning Chemistry fun!</b>
</p>
