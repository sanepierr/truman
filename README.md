# Truman Bed & Mattress

The official marketing website for **Truman Bed & Mattress**, showcasing the premium Truman Hybrid mattress through an elegant, mobile-optimized, and interactive digital experience.

## Features

- **High-Fidelity Mobile Design**: Fully responsive, mobile-first layouts featuring compact grids, beautiful typography, and full-bleed hero sections.
- **Interactive Layer Anatomy**: A scroll-triggered, visually stunning animation that reveals the 8 layers of the Truman Hybrid mattress, complete with dynamic callouts and a "pocket" assembly effect.
- **Direct WhatsApp Integration**: A streamlined contact inquiry form that dynamically generates personalized messages and opens directly in a WhatsApp chat for immediate customer service.
- **Integrated Blog/Articles**: Seamless in-page article reading experiences with elegant overlay transitions and back-navigation.

## Stack

- **Framework**: Vite + React
- **Architecture**: A static HTML/CSS/JS frontend served dynamically via a minimal React application wrapper.
- **Styling**: Vanilla CSS utilizing custom CSS variables for design tokens (`--charcoal`, `--gold`, `--sage`, `--linen`) to maintain a cohesive, premium brand aesthetic.

## Local Development

```bash
npm install
npm run dev
```

## Production Build

```bash
npm run build
npm run preview
```

## Project Structure

- `public/original-site.html` - The core website file containing all markup, styles, and interactive scripts.
- `public/article1-4.html` - Dedicated blog article pages designed with immersive overlays.
- `public/favicon.svg` - The Truman brand logo.
- `public/uploads/` & `public/new_batch/` - High-resolution image assets and promotional media.
- `src/` - The minimal React wrapper application for local dev and build processes.

## Deployment (Vercel)

- **Framework preset**: `Vite`
- **Build command**: `npm run build`
- **Output directory**: `dist`

*Note: If importing from the parent mono-folder, ensure the Vercel Root Directory is set to `project/truman`.*
