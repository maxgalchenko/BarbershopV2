# BarbershopV2

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![Gulp](https://img.shields.io/badge/Gulp-CF4647?style=for-the-badge&logo=gulp&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000)
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=webpack&logoColor=000)
![BrowserSync](https://img.shields.io/badge/BrowserSync-CC2E92?style=for-the-badge&logo=browsersync&logoColor=white)

</div>

## Overview

A static, responsive barbershop website template. Built with SCSS and a Gulp-based pipeline that compiles, bundles, and optimizes assets into `docs/` for easy hosting (e.g., GitHub Pages).

## Key Features

- Responsive layout with modular SCSS partials
- Asset optimization: minified CSS/JS, image compression, and WebP generation
- Live-reload dev server powered by BrowserSync

## Tech Stack

HTML5, SCSS, JavaScript (ES6), Gulp 4, PostCSS (Autoprefixer, cssnano), Webpack 4, BrowserSync

## Architecture

Source files live in `src/` (`sass`, `js`, `img`, `*.html`). Gulp tasks compile and output production-ready assets to `docs/`, including HTML minification, CSS/JS bundling, and images (JPG/PNG/WebP).

## Performance & Accessibility

Minified bundles, PostCSS optimizations, and WebP images reduce payload size. Semantic HTML and basic ARIA patterns aim to improve keyboard and screen reader support.

## Prerequisites

- Node.js: `12.22.12`

## Installation

```bash
git clone https://github.com/Rainspistols/BarbershopV2.git
cd BarbershopV2
npm install
```

## Quick Start

```bash
npm run dev
# Production
npm run build
npm start
```

Open http://localhost:3000

## Available Scripts

- `npm run dev` – Start BrowserSync with file watching and live reload
- `npm run build` – Clean and build optimized assets into `docs/`
- `npm start` – Alias of `dev`

## Screenshots

![Main](./src/img/screenshots/localhost_3003_main.html.png)

![Booking](./src/img/localhost_3003_pages_booking.html.png)

![Photo](./src/img/localhost_3003_pages_photo.html.png)

---

<div align="center">

Built with ❤️ by [Maksym Galchenko](https://github.com/maxgalchenko)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/galchenko-max/)

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-green?style=for-the-badge&logo=web)](https://portfolio-green-six-29.vercel.app/)

[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:galchenko.maksym@gmail.com)

![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

</div>
