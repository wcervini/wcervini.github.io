# wcervini.github.io

[![Astro](https://img.shields.io/badge/built%20with-Astro-FF5D01?logo=astro)](https://astro.build)
[![Deploy](https://github.com/wcervini/wcervini.github.io/actions/workflows/deploy.yml/badge.svg)](https://github.com/wcervini/wcervini.github.io/actions/workflows/deploy.yml)

Personal portfolio site built with [Astro](https://astro.build). Hosted on GitHub Pages.

## 🚀 Quick start

```bash
npm install
npm run dev
```

Open [localhost:4321](http://localhost:4321) in your browser.

## 📦 Commands

| Command           | Action                               |
| ----------------- | ------------------------------------ |
| `npm install`     | Install dependencies                 |
| `npm run dev`     | Start dev server at `localhost:4321` |
| `npm run build`   | Build the site to `dist/`            |
| `npm run preview` | Preview the production build locally |

## 🧱 Project structure

```
src/
├── components/   # Header, Hero, Projects, Skills, Footer
├── layouts/      # Base HTML layout
├── pages/        # Site pages (index.astro)
└── styles/       # Global styles (global.css)
```

## 🚢 Deployment

The site is automatically deployed to GitHub Pages via GitHub Actions on every push to the `master` branch.

## 📄 License

[MIT](./LICENSE)
