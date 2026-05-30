# 📊 VTU SGPA & CGPA Calculator — Expressive Edition

A state-of-the-art, glassmorphic single-page web application designed for Visvesvaraya Technological University (VTU) students to calculate and audit their SGPA and CGPA seamlessly. Completely self-contained, lightweight, and offline-compatible with zero external dependencies.

---

### 🌐 Live Portal
👉 **[Launch the Live Calculator](https://arm-x-dev.github.io/vtu-sgpa-calculator/)**

---

## 🚀 Badges

![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Yes-success?style=for-the-badge&logo=responsive)
![Aesthetics](https://img.shields.io/badge/Aesthetics-Glassmorphic--Modern-purple?style=for-the-badge)
![Status](https://img.shields.io/badge/Build-Passing-brightgreen?style=for-the-badge)

---

## ✨ Features

### 🌌 1. Ultra-Modern Responsive Interface
* **Interactive Physics Background:** Fully responsive fullscreen HTML5 `<canvas>` particle mesh background that dynamically connects and repels on mouse hover.
* **3D Glass Choice Cards:** Staggered, cascading menu cards featuring realistic 3D cursor-following tilt parallax sheens.
* **Cohesive Premium Presets:** Glass pill theme switcher supporting **Cyberpunk Neon**, **Sunset Glow**, **Emerald Forest**, and **Arctic Aurora** colorways.

### 📝 2. Intelligent SGPA Spreadsheet Calculator
* **Dual Curriculums:** Features ECE preloaded semester schemes alongside a fully Custom Mode for other engineering branches.
* **Audit / Non-Credit Toggle:** Designated check toggles to instantly exclude individual subjects from SGPA calculations.
* **Smart Marks CIE/SEE Auto-Scaling:** Enter marks out of 100 directly; scores exceeding 50 are automatically scaled down to 50 in real-time, displaying a direct sum (`CIE + SEE = 100`).
* **Micro Health Metrics:** Inline progress meters displaying performance percentage breakdowns directly beneath subject rows.

### 🎓 3. Weighted CGPA Calculator
* **Multi-Semester Audit:** Dynamic 8-semester calculator applying the official VTU credit-weighted formula:  
  $$\text{CGPA} = \frac{\sum (S_i \times C_i)}{\sum C_i}$$
* **Arbitrary Range Evaluation:** Defaulting initial credits to `0` so uncompleted terms are automatically ignored, enabling effortless partial audits.

### 📱 4. Responsive Screen Optimization
* **Buttonless Direct Typing:** Wide increment buttons and flex containers removed to yield a sleek `60px` standalone input grid.
* **Single-Line Fitment:** Compact tables fit subject names, codes, and points on a single, continuous line without horizontal scrollbars on mobile.
* **Numeric Keypad Integration:** Standardizes `inputmode="decimal"` and `inputmode="numeric"` to trigger mobile numeric pads instantly.

### 📄 5. Personal Transcript & Security
* **PDF Exporter:** Wires radial gauge charts, tick counters, and confetti loops into clean, print-ready, print-formatted HTML academic transcripts.
* **Security Lock:** Built-in global context-menu blocker to provide a clean kiosk/web-app feel.

---

## 🛠️ Tech Stack

* **Frontend Structure:** HTML5 (Semantic elements & SVG)
* **Styling & Theme Engine:** Vanilla CSS3 (Custom CSS Custom Properties, flexbox/grid layouts, keyframe animations)
* **Mathematical & Interactive Logic:** Vanilla JavaScript (Dependency-free canvas rendering & mathematical calculators)
* **Deployment System:** GitHub Pages

---

## 📖 How to Use

1. **Launch** the web portal.
2. **Choose Your Path:** Select **SGPA Calculator (ECE)**, **Custom Calculator (Manual)**, or **CGPA Calculator (Multi-Sem)**.
3. **Feed the Fields:** Type in your marks, credits, or SGPAs. Fields automatically auto-highlight on click for instant corrections.
4. **Observe Real-Time Changes:** Footer sums, grades, and total credit points recalculate instantly with every keystroke.
5. **Export & Print:** Hit the download action to save a beautifully styled academic record sheet.

---

## 🔧 Installation & Local Setup

Run the project locally without any complex compilations or build tooling:

```bash
# Clone the repository
git clone https://github.com/arm-x-dev/vtu-sgpa-calculator.git

# Navigate into the project directory
cd vtu-sgpa-calculator

# Launch the index.html file in any web browser
open index.html
