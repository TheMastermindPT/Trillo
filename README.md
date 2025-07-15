# Trillo

I built Trillo as a fully responsive hotel booking landing page to demonstrate advanced CSS architecture and modern frontend workflow. This project let me apply modular SCSS, CSS Grid, and Flexbox to create a visually engaging, interactive UI from scratch. My focus was on mastering layout, clean code organization, and micro-animations—without relying on any backend logic. Trillo exists as a portfolio and learning piece, reflecting my approach to scalable, maintainable frontend design.

![Trillo Preview](./dist/images/hotel-1.jpg) <!-- Replace with your uploaded GIF if desired -->

---

## Features

- Fully responsive layout using **CSS Grid** and **Flexbox**
- Modular SCSS architecture (BEM-based)
- Smooth transitions and **micro-interactions**
- Webpack 4 bundling with Babel and PostCSS
- Organized production-ready asset pipeline

---

## 📁 Project Structure

```
Trillo/
├── css/                        # Compiled CSS output
│   └── main.css
├── dist/                       # Distribution-ready assets
│   ├── images/                 # Hotel and user images
│   │   ├── hotel-1.jpg
│   │   ├── user-1.jpg
│   │   └── ...
│   └── index.html              # Main HTML file
├── scss/                       # SCSS source files
│   ├── abstracts/              # Sass helpers: variables, mixins, functions
│   ├── base/                   # Base styles: typography, resets
│   ├── components/             # UI components: buttons, cards, etc.
│   ├── layout/                 # Layout-related styles: header, footer, grid
│   ├── pages/                  # Page-specific styles (if any)
│   └── main.scss               # Root SCSS file (imports everything)
```

---

### 1. Install dependencies
```bash
npm install
```

## Start development server

```bash
npm run build-css      # Watches and compiles SCSS
npm run dev-server     # Starts Webpack dev server with live reload
```

## Build for production
`npm run build          # Compiles and optimizes output for dist/`
