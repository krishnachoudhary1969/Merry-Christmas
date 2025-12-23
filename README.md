# 🎄 Merry Christmas – Animated SVG Tree ✨
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=for-the-badge&logo=javascript)
![GSAP](https://img.shields.io/badge/GSAP-Animation-88CE02?style=for-the-badge&logo=greensock)
![HTML5](https://img.shields.io/badge/HTML5-SVG-E34F26?style=for-the-badge&logo=html5)
![CSS3](https://img.shields.io/badge/CSS3-Styling-1572B6?style=for-the-badge&logo=css3)
![Christmas](https://img.shields.io/badge/🎄-Christmas%20Vibes-red?style=for-the-badge)

Ho ho ho! 🎅  
Welcome to **Merry Christmas**, a festive front-end project that brings holiday cheer to life using **SVG animations**, **GSAP**, and a whole lot of sparkle ❄️✨.

This project renders a beautifully animated **Christmas Tree** where:
- The tree is *drawn dynamically*
- A glowing star animates along the tree path
- Festive particles (stars, hearts, circles & crosses) burst into life
- Everything runs smoothly with GSAP timelines

Sit back, relax, and enjoy the Christmas magic 🎁🎶

---

## 🎥 Live Preview

🔗 **Open `index.html` in your browser**  
(Works best on desktop for full animation glory ✨)

---

## 🌟 Features

🎄 SVG-based animated Christmas Tree  
✨ Smooth GSAP animations & timelines  
❄️ Particle effects with physics-based motion  
⭐ Animated glowing star following the tree path  
🎨 Minimal & dark festive background  
⚡ Lightweight & pure front-end (no backend required)

---

## 🛠️ Tech Stack

- **HTML5** – SVG structure & layout  
- **CSS3** – Styling & layout control  
- **JavaScript (ES6)** – Animation logic  
- **GSAP 3** –  
  - MotionPathPlugin  
  - DrawSVGPlugin  
  - MorphSVGPlugin  
  - Physics2DPlugin  
  - EasePack  

---

## 📁 Project Structure

Merry-Christmas/
│
├── index.html # Main SVG structure & script imports
├── style.css # Page styling & layout
├── script.js # GSAP animations & particle logic
└── README.md # You are here 🎄

---

## 🎄 How It Works (Behind the Scenes)

- The **tree is an SVG path** that gets drawn using `DrawSVGPlugin`
- A **star container** follows the tree path using `MotionPathPlugin`
- As the star moves, **particles are emitted** using GSAP’s `Physics2DPlugin`
- Randomized colors, shapes & gravity give it a lively festive feel
- The animation is controlled via a **master GSAP timeline**

Everything syncs together for a smooth holiday animation ✨

---

## 🚀 How to Run Locally

1. Clone the repository
   ```bash
   git clone https://github.com/krishnachoudhary1969/Merry-Christmas.git
2. Open the folder
   ```bash
   cd Merry-Christmas
3. Open index.html in your browser (No server required 🎉)

