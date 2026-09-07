# Nazmul Hassan — Personal Portfolio

![Portfolio Preview](assets/images/profile.jpg)

A clean, modern, and responsive personal portfolio website developed with **100% Vanilla HTML5, CSS3, and JavaScript** (no libraries or frameworks), adhering strictly to the requirements of **CSE 471: Web and Internet Programming (Summer 2026)**.

---

## 🌐 Live Demonstration & Repository Links
- **Public GitHub Repository**: [https://github.com/nazmulhf58-dot/Portfolio](https://github.com/nazmulhf58-dot/Portfolio)
- **Live Deployment (GitHub Pages)**: [https://nazmulhf58-dot.github.io/Portfolio/](https://nazmulhf58-dot.github.io/Portfolio/)

---

## 📌 Project Overview
- **Student Name**: Nazmul Hassan
- **Course**: CSE 471 — Web and Internet Programming
- **Semester**: Summer 2026
- **Marks**: 10
- **Assessment**: Assignment (Personal Portfolio Website Development & Deployment)

---

## 🚀 Key Features
- **Pure Vanilla Web Stack**: 100% hand-crafted HTML5, CSS3, and Vanilla JavaScript. Zero external frameworks or CSS preprocessors (no React, Bootstrap, Tailwind, jQuery, etc.).
- **Dynamic Dark & Light Mode**: Seamless theme switching with system auto-detection, animated toggle, and persistent `localStorage` preference.
- **Responsive Layout**: Optimized across Mobile (<640px), Tablet (641px–1024px), and Desktop (>1024px) screens using CSS Grid, Flexbox, and fluid typography (`clamp()`).
- **Interactive Tech Stack Marquee**: Smooth infinite CSS marquee showcasing core technologies.
- **Filterable Project Showcase**: Category filter system (All, Full Stack, Frontend, Algorithmic / Systems) with smooth transitions.
- **Interactive Project Modal (`<dialog>`)**: Accessible detail view modal with light-dismiss backdrop support.
- **Animated Metrics Counter**: Dynamic counter triggered via `IntersectionObserver` when scrolled into viewport.
- **Contact Form Validation & Toast Notification**: Client-side form validation with real-time feedback and animated toast notification upon submission.
- **Typewriter Text Effect**: Dynamic rotating titles in the hero section.

---

## 📂 Project Structure
```text
portfolio/
├── index.html              # Main HTML5 semantic structure
├── README.md               # Project documentation & assignment details
├── SUBMISSION_REPORT.md    # Formatted course submission report
├── css/
│   └── style.css           # Vanilla CSS3 styles, variables & responsive design
├── js/
│   └── main.js             # Vanilla ES6+ interactivity & state management
└── assets/
    ├── icons/
    │   └── favicon.svg     # SVG logo favicon
    ├── images/
    │   ├── profile.jpg     # Professional portrait photo
    │   ├── project-1.jpg   # CodeFlow collaboration platform preview
    │   ├── project-2.jpg   # CodeSolve online judge platform preview
    │   ├── project-3.jpg   # Aurora tech marketplace preview
    │   └── project-4.jpg   # Climate AI analytics dashboard preview
    └── docs/
        └── CV_Nazmul_Hassan.pdf # Curriculum Vitae
```

---

## 🛠️ Local Development
To run this project locally without any dependencies:
1. Clone the repository:
   ```bash
   git clone https://github.com/nazmulhf58-dot/Portfolio.git
   cd Portfolio
   ```
2. Open `index.html` in any modern web browser or serve it using Python/VS Code Live Server:
   ```bash
   # Python 3
   python -m http.server 3000
   ```
3. Visit `http://localhost:3000` in your browser.
