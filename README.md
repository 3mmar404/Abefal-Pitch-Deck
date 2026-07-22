<div align="center">

# 📊 Abefal — Pitch Deck

**An interactive, single-page business presentation for Abefal Global Tech — detailing the exclusive franchise strategy for Novker products in Egypt, with comprehensive market analysis, financial models, and operational plans.**

[![Live Demo](https://img.shields.io/badge/Live_Demo-View_Pitch-0A7E8C?style=for-the-badge&logo=githubpages&logoColor=white)](https://3mmar404.github.io/Abefal-Pitch-Deck//)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](#-tech-stack)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](#-tech-stack)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](#-tech-stack)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38BDF8?style=flat-square&logo=tailwindcss&logoColor=white)](#-tech-stack)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)](#-tech-stack)
[![License: MIT](https://img.shields.io/badge/License-MIT-3DA639?style=flat-square)](#-license)

</div>

---

## Overview

**Abefal Pitch Deck** is a comprehensive, single-page web presentation designed to showcase the establishment of the Egyptian branch of Abefal Global Tech — the exclusive franchisee for Novker fiber optic fusion splicers and testing equipment in the Middle East. The deck delivers a complete business narrative covering executive summary, business model canvas, investor plan, financial projections, legal compliance, operational strategy, and detailed market analysis.

Built with pure HTML, CSS, and JavaScript (with Tailwind CSS and Chart.js for styling and data visualization), the presentation features a multi‑tab interface, an interactive document viewer with chapter navigation, dynamic charts, and full Arabic (RTL) support. The pitch deck serves as both a living business plan and a sales enablement tool for the venture.

> **Live site:** https://3mmar404.github.io/Abefal-Pitch-Deck//

---

## Features

- 📑 **Multi‑tab presentation** — six main sections: Compass (Executive Summary), Business Model, Investor Plan, Financial Indicators, Full Documentation, and References
- 📱 **Fully responsive** — optimized for desktop, tablet, and mobile devices with a collapsible navigation menu
- 🧭 **Interactive document viewer** — chapter-based sidebar navigation for the comprehensive documentation section (9 chapters)
- 📊 **Data visualizations** — dynamic charts powered by Chart.js (cost breakdown, revenue projections, monthly cash flow)
- 🌍 **Multi‑language support** — integrated Google Translate toggle for Arabic, English, and German
- 🎨 **Dark theme with accent colors** — corporate dark palette with cyan/blue accents for a premium, tech‑focused aesthetic
- 📄 **Rich content** — detailed tables, competitor benchmarking, financial models, legal frameworks, and go‑to‑market strategies
- ⚡ **Lightweight & fast** — no heavy frameworks; Tailwind CSS loaded via CDN, vanilla JavaScript for interactivity

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Markup | HTML5 (semantic, `dir="rtl"`) |
| Styling | Tailwind CSS (via CDN) + custom CSS for scrollbars, animations, and dark theme |
| Charts | Chart.js (via CDN) |
| Icons | Font Awesome 6.4.0 |
| Behavior | Vanilla JavaScript (ES6) — tab switching, mobile menu, document navigation, language toggle |
| Translation | Google Translate API (embedded) |
| Hosting | GitHub Pages |

No build tools, no frameworks — runs directly from static files.

---

## Getting Started

Clone the repository and open it locally.

```bash
# 1) Clone
git clone https://github.com/3mmar404/abefal-pitch-deck.git
cd abefal-pitch-deck
Option A — open directly

Just open index.html in your browser.

Option B — run a local server (recommended for correct asset paths)

bash
# Python 3
python3 -m http.server 8000

# …or Node
npx serve .
Then visit http://localhost:8000.

Project Structure
text
abefal-pitch-deck/
├── index.html          # Main presentation — all content in a single page
├── README.md           # This file
└── (no additional assets — all CDN-loaded)
Note: All styles, scripts, fonts, and icons are loaded via CDN. No external images or asset files are required.

Content Overview
The presentation is divided into six main tabs:

Tab	Content
Compass	Executive summary — What, Why, Who, Where, When, How, How Much
Business Model	Full Business Model Canvas with 8 building blocks, KPIs, competitive advantage, and 3‑year roadmap
Investor Plan	Problem/solution, market analysis, competitor benchmarking, go‑to‑market strategy, risk matrix, and investment summary
Financials	Financial feasibility study — CAPEX, OPEX, unit economics, revenue forecasts, cash flow analysis, and ROI
Full Document	9‑chapter comprehensive documentation covering fiber optics technology, franchise model, product deep‑dive, market environment, customer analysis, legal compliance, operations, logistics, and GTM strategy
References	Official links to NTRA, GOEIC, NAFEZA, GAFI, WE, contractor databases, and technical standards
Customization
Changing Content
Edit the sections inside index.html — each tab (#compass, #business-model, #investor-plan, #financials, #full-doc, #references) contains its own HTML structure.

Updating Colors
The Tailwind configuration is embedded in the <head>:

html
<script>
  tailwind.config = {
    theme: {
      extend: {
        colors: {
          corporate: {
            900: '#0f172a',
            800: '#1e293b',
            700: '#334155',
            accent: '#06b6d4',
            accentHover: '#0891b2',
          }
        }
      }
    }
  }
</script>
Adding Charts
Chart.js charts are initialized in the main <script> block at the bottom of the page. To add or modify charts, update the corresponding new Chart() calls.

Contributing
Contributions, issues, and feature requests are welcome!

Fork the repository

Create a feature branch (git checkout -b feature/your-feature)

Commit your changes (git commit -m "Add your feature")

Push the branch (git push origin feature/your-feature)

Open a Pull Request

</div> ```
License
This project is licensed under the MIT License — see the LICENSE file for details.

<div align="center">
Designed & developed with ❤️ for the Abefal brand · © 2026 Ahmed Amar (@3mmar404)

