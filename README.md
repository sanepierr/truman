# Truman Website

Marketing website for Truman Bed & Mattress.

## Stack

- Vite + React
- Static page served from `public/original-site.html` via the React app shell

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

- `public/original-site.html` - main website markup/styles/scripts
- `public/uploads/` - image assets used by the website
- `src/` - minimal React wrapper app

## Deployment (Vercel)

- Framework preset: `Vite`
- Build command: `npm run build`
- Output directory: `dist`

If importing from the parent mono-folder, set Vercel Root Directory to:

`project/truman`
