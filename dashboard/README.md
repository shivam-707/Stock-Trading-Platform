# Dashboard

A React dashboard application built with Vite.

This repository contains the `dashboard` frontend package for the Zerodha project. It uses React 19 for a fast development experience with hot module replacement.

## Features

- React 19 app powered by Vite
- Fast dev server with HMR
- Build-ready output via Vite
- ESLint configuration for basic linting

## Project structure

- `src/` – React application source files
- `public/` – static assets served by Vite
- `package.json` – package metadata and scripts
- `vite.config.js` – Vite configuration
- `README.md` – project documentation

## Getting started

### Prerequisites

- Node.js 18+ or later
- npm 10+ or a compatible package manager

### Install dependencies

```bash
cd dashboard
npm install
```

### Run development server

```bash
npm run dev
```

Open the URL shown in the terminal to view the app in the browser.

### Build for production

```bash
npm run build
```

### Preview production build

```bash
npm run preview
```

### Run linting

```bash
npm run lint
```

## Customization

- Edit `src/App.jsx` to update the main app content.
- Update styles in `src/App.css` and `src/index.css`.
- Add new components under `src/components` as needed.

## Notes

- This project currently includes only React and React DOM as runtime dependencies.
- Vite is configured with `@vitejs/plugin-react` for React JSX support.
- The current app includes a sample counter and documentation links.

## Useful links

- Vite: https://vite.dev/
- React: https://react.dev/

---

If you want, I can also add a `Contribution` section or integrate a more detailed `Project Setup` guide for this repository.
