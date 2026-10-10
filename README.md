# Pocket Universe — Phase 2

Interactive space exploration website built with React + TypeScript + Three.js.

## Prerequisites

- Node.js 18 or later
- npm 9 or later

## Setup

```bash
npm install
```

## Development

```bash
npm run dev
```

Opens at http://localhost:5173

## Production build

```bash
npm run build
```

Output is in `dist/`.

## Type-check only

```bash
npm run typecheck
```

## What's in Phase 2

- Cinematic hero section with an animated 3D solar system (React Three Fiber)
- Seven planets with correct orbital mechanics
- Scroll-driven feature cards
- Navigation with mobile hamburger menu
- WebGL fallback for unsupported browsers
- Reduced-motion support
- Responsive layout (mobile / tablet / desktop)
- CSS design system (custom properties, no CSS-in-JS runtime)
- Zustand stores for UI, simulation, and mission state
- localStorage persistence for mission progress

Phases 3–5 (Orbit Lab, Physics Experiments, Mission Mode) arrive in subsequent phases.
