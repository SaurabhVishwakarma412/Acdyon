# FlowPilot

## Overview

FlowPilot is a frontend-only concept for a workflow automation intelligence platform.

## Features

- Responsive premium landing page with persistent light and dark themes
- Interactive workflow-run simulation
- Product dashboard made from React components and clearly labelled example data
- Mobile navigation, keyboard controls, and reduced-motion support

## Tech Stack

React 19, Vite, and CSS.

## Getting Started

```bash
npm install
npm run dev
```

## Production Build

```bash
npm run build
```

## Deployment

Import the repository into Vercel. Its standard Vite preset uses `npm run build` and publishes `dist`.

## Architecture

`src/App.jsx` holds small reusable UI components for navigation, dashboard preview, and workflow runner. `src/index.css` owns design tokens and responsive behavior.

## Design Decisions

See [DECISIONS.md](./DECISIONS.md).
