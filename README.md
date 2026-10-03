# Cetro React Project

A modern React + Vite landing page for a cleaning agency brand ("Cetro"), built with Tailwind CSS and animated UI sections.

## Tech Stack

- React 19
- Vite 8
- Tailwind CSS 4 (`@tailwindcss/vite`)
- Lucide React + React Icons
- ESLint 9

## Features

- Responsive, section-based landing page
- Animated hero and scroll-triggered section animations
- Reusable UI components (`Header`, `Hero`, `About`, `Services`, `Footer`, etc.)
- Mobile-friendly navigation drawer and action bar

## Project Structure

```text
src/
  components/    # UI sections and reusable components
  hooks/         # Custom hooks (e.g., scroll animation logic)
  assets/        # Images and static assets
  App.jsx        # Main page composition
  main.jsx       # Application entry point
```

## Getting Started

### 1) Install dependencies

```bash
npm install
```

### 2) Run in development

```bash
npm run dev
```

### 3) Build for production

```bash
npm run build
```

### 4) Preview production build

```bash
npm run preview
```

## Linting

Run ESLint:

```bash
npm run lint
```

## Notes

- Global styles and animation utilities are defined in `src/index.css`.
- Tailwind is configured via the Vite plugin in `vite.config.js`.
