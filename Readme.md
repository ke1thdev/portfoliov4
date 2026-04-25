<div align="center">
  <svg width="600" height="100" xmlns="http://www.w3.org/2000/svg">
    <rect width="100%" height="100%" fill="#111" rx="10" />
    <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle" font-family="Courier New, monospace" font-size="28" fill="#fff" font-weight="bold">Keith | Personal Portfolio</text>
  </svg>
</div>

<br />

<div align="center">
  <a href="https://ke1th.dev">
    <img src="https://img.shields.io/badge/Website-ke1th.dev-black?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live Website" />
  </a>
  <a href="https://github.com/ke1thdev">
    <img src="https://img.shields.io/badge/GitHub-Profile-black?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Profile" />
  </a>
</div>

<br />

## Project Overview

This repository holds the source code for my personal web portfolio. The live demo is accessible via **[https://ke1th.dev](https://ke1th.dev)**. It acts as the main landing page for my professional history, academic background in Computer Science, and software engineering projects. I built this site with a focus on performance, clean layout, and minimal yet modern visual design. 

## Technical Setup

The project relies on standard front-end tools without heavy build steps, ensuring simple maintenance and high browser compatibility.

<p align="left">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" title="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" title="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" title="JavaScript" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP" title="PHP" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" title="Python" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" title="MySQL" />
</p>

* **Structure & UI**: HTML5, CSS3, and the [Bootstrap](https://getbootstrap.com/) framework.
* **Logic & Interactivity**: Vanilla JavaScript, [jQuery](https://jquery.com/), and [Typed.js](https://mattboldt.github.io/typed.js/) for terminal-style typing effects.
* **Fluid Motion**: [AOS (Animate on Scroll)](https://michalsnik.github.io/aos/) for scroll-triggered entrance animations.
* **Background Visuals**: [Particles.js](https://vincentgarreau.com/particles.js/) for the dynamic interactive background.
* **Iconography**: [Boxicons](https://boxicons.com/) and [Remix Icon](https://remixicon.com/) for a sleek, uniform visual language.

## Repository Structure

To maintain a clean development environment, the project is organized as follows:

```text
├── assets/
│   ├── css/              # Core stylesheets including custom glassmorphism overrides
│   ├── js/               # Main logic and vendor initialization scripts
│   ├── img/              # Optimized project thumbnails and brand assets
│   ├── vendor/           # Third-party libraries (Bootstrap, AOS, Owl Carousel)
│   └── fonts/            # Localized Google Fonts for offline performance
├── index.html            # Primary entry point
└── sitemap.xml           # SEO configuration
```

## Core Features

* **High-Performance Responsiveness**: The grid system is fully optimized for everything from ultra-wide 4K monitors to small mobile screens.
* **Modern Aesthetic**: Implements a glassmorphism design language using `backdrop-filter` and translucent color palettes.
* **Optimized Loading**: Assets are delivered with efficient heading structures and minimized layout shifts.
* **Automated SEO**: Integrated sitemap and meta-tag optimization for better search engine indexing.
* **Interactive Components**: Categorized portfolio filtering and real-time form validation.

## Developer Profile

I am a third-year Computer Science student concentrating on Full Stack Web Development. I regularly code in PHP, Python, and JavaScript. My approach is straightforward: I prioritize reliable, working code over over-engineered theoretical concepts.

**Key Highlight**: Awarded the **Domain MVP – Reverse Engineering** title at the Web5 Development Hackathon 2025 (Season 3) hosted at DEBESMSCAT.

## Featured Software

The website showcases several systems I have built and maintained:

1. **Attendance Tracker**: A secure web system used for logging and viewing student attendance records.
2. **Istorya**: A real-time, random chat web application modeled for campus-specific networking.
3. **Fees Management System**: A financial tracking dashboard developed to process student accounts.
4. **eGrade System**: A streamlined portal allowing students to review academic grades securely.
5. **Alternative Projects**: Various standalone scripts and games, including a photobooth web application, Slapnmoan (desktop interaction app), and a Flappy Bird clone configured to run via hand-tracking algorithms (OpenCV/MediaPipe).

## Local Testing

If you want to run this portfolio locally to inspect the code or test changes:

1. Clone this repository to your machine:
   ```bash
   git clone https://github.com/ke1thdev/portfoliov4.git
   ```
2. Open the created directory:
   ```bash
   cd portfoliov4
   ```
3. Start a basic web server. Avoid opening the `index.html` file directly as `file://` if you want local fetch requests and assets to load properly. For example, using Python:
   ```bash
   python -m http.server 8000
   ```
4. Access `http://localhost:8000` via your browser.

## License Status

This codebase is open-sourced under the MIT License. Please refer to the `LICENSE` file for the exact terms.
