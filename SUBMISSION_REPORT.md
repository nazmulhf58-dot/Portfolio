# ASSIGNMENT SUBMISSION REPORT

**Course Code**: CSE 471  
**Course Title**: Web and Internet Programming  
**Semester**: Summer 2026  
**Marks**: 10  
**Student Name**: Nazmul Hassan  
**Assessment**: Personal Portfolio Website Development & Deployment  

---

## 1. SUBMISSION LINKS

- **(1) Public GitHub Repository Link**:  
  [https://github.com/nazmulhf58-dot/Portfolio](https://github.com/nazmulhf58-dot/Portfolio)

- **(2) Live Deployed Website Link (GitHub Pages)**:  
  [https://nazmulhf58-dot.github.io/Portfolio/](https://nazmulhf58-dot.github.io/Portfolio/)

---

## 2. ORIGINALITY & REQUIREMENT COMPLIANCE STATEMENT

All code, design architecture, styling, and interactivity implemented in this portfolio were crafted independently from scratch using **100% Vanilla HTML5, CSS3, and JavaScript (ES6+)**. 

- **Frameworks / Libraries Used**: **None (0%)**.  
  - No React, Vue, Angular, Svelte  
  - No Tailwind CSS, Bootstrap, Bulma, Foundation  
  - No jQuery, Lodash, Axios, Framer Motion, GSAP  
- **Visual Design**: Inspired by clean modern portfolio aesthetics (such as [rsriad.dev](https://www.rsriad.dev/)), tailored specifically with a personalized dark obsidian / light theme, custom profile identity card, and fluid CSS layout.
- **Responsiveness**: Fully responsive across mobile (<640px), tablet (641px–1024px), and desktop (>1024px) screens using CSS Grid, Flexbox, and fluid `clamp()` sizing.
- **Interactive JavaScript Features**:
  1. **Dark & Light Mode Theme Switcher**: System color-scheme detection, animated sun/moon toggle, and persistence across sessions via `localStorage`.
  2. **Active Scrollspy Navigation**: Dynamic floating pill header that blurs on scroll and tracks section visibility using `IntersectionObserver`.
  3. **Animated Hero Typewriter**: Multi-phrase rotating typewriter without third-party scripts.
  4. **Dynamic Project Category Filter**: Seamlessly filters projects by category (All, Full Stack, Frontend, Systems) with smooth CSS transitions.
  5. **Accessible Project Details Modal (`<dialog>`)**: Native modal dialog with light-dismiss backdrop support and custom feature breakdown.
  6. **Animated Statistics Counter**: Triggers numeric count-up animation when metrics scroll into viewport.
  7. **Real-time Contact Form Validation**: Live input validation with error messages, submit button loading spinner, and animated Toast Notifications.
  8. **Floating Back-to-Top Button**: Smooth scrolling controller that appears dynamically after scrolling 400px.

---

## 3. GIT INCREMENTAL COMMIT HISTORY LOG

The project was developed in incremental milestones rather than a bulk commit, satisfying the requirement of **5–7 minimum meaningful commits**:

```text
* commit 1986ea4 - feat: Add authentic user profile photograph and optimize portrait framing
* commit 65da337 - docs: Finalize portfolio documentation, deployment guide, and submission report
* commit 266a60a - feat(js): Add theme toggle, scrollspy, typing effect, modal dialog, and form validation
* commit 008b1ef - feat: Add toast notification, back-to-top button, and comprehensive responsive media queries
* commit 2372a04 - feat: Add experience, education timeline, and contact section with form validation styles
* commit 61d107b - feat: Implement filterable project showcase with cards and action buttons
* commit fe4891a - feat: Add tech stack showcase with infinite marquee and animated metrics counter
* commit 0758710 - feat: Implement responsive floating navigation and hero section with profile card
* commit d5b6d44 - feat: Add CSS design tokens, light/dark theme variables, and global reset
* commit fe3329d - chore: Initial project setup, README, assets, and HTML5 semantic structure
```

---

## 4. SCREENSHOTS SUBMISSION GUIDE

To attach the required screenshots for submission:

### (3) Screenshots of Source Code
- **HTML5 Structure (`index.html`)**: Showing semantic tags (`<header>`, `<main>`, `<section>`, `<article>`, `<dialog>`, `<footer>`).
- **Vanilla CSS3 (`css/style.css`)**: Showing `:root` tokens, dark/light theme definitions, `@keyframes marqueeScroll`, and `@media` queries.
- **Vanilla JavaScript (`js/main.js`)**: Showing `IntersectionObserver` scrollspy, modal handling, and contact form validation logic.

### (4) Screenshots of Rendered Website
- **Desktop View (Dark Theme)**: Hero section, floating navbar, and identity profile card.
- **Desktop View (Light Theme)**: Showcase of the dynamic theme toggle in action.
- **Tech Stack & Skills Section**: Infinite marquee and categorized skill cards.
- **Projects Section & Interactive Modal**: Filter tabs and opened `<dialog>` modal showing project technical highlights.
- **Contact Form Validation**: Real-time error alerts and success toast notification.
- **Mobile Responsive View**: Rendered on iPhone / Android viewport showing hamburger menu drawer and single-column layout.

### (5) Screenshot of GitHub Commit History
- A screenshot from GitHub web UI: `https://github.com/nazmulhf58-dot/Portfolio/commits/main` demonstrating the incremental commit history.

---

## 5. DEPLOYMENT INSTRUCTIONS (GITHUB PAGES)

To activate GitHub Pages for this repository:
1. Go to your GitHub repository: `https://github.com/nazmulhf58-dot/Portfolio`
2. Click on **Settings** &rarr; **Pages** (in the left sidebar).
3. Under **Build and deployment** &rarr; **Source**:
   - Select **Deploy from a branch**.
   - Branch: select `main` and folder `/ (root)`.
   - Click **Save**.
4. In ~1–2 minutes, your website is live at:  
   **`https://nazmulhf58-dot.github.io/Portfolio/`**
