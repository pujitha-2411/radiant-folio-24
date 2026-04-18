# Radiant Folio 24

A modern portfolio web app built with **React + TypeScript** using **TanStack Start** and **Vite**.

## Overview
This project contains the source code for my personal portfolio—projects, experience, and ways to contact me.

## Tech Stack
- **TypeScript**
- **React**
- **TanStack Start / Router / Query**
- **Vite**
- **Tailwind CSS**
- **Supabase** (backend/auth/db as needed)
- **Cloudflare** tooling (via `@cloudflare/vite-plugin` / `wrangler.jsonc`)

## Scripts
- `dev` — start the dev server
- `build` — production build
- `build:dev` — development-mode build
- `preview` — preview the production build locally
- `lint` — run ESLint
- `format` — run Prettier

## Getting Started

### Install
Using **bun** (recommended if you already use bun):
```bash
bun install
```

Or using **npm**:
```bash
npm install
```

### Development
```bash
bun run dev
# or
npm run dev
```

### Build
```bash
bun run build
# or
npm run build
```

### Preview
```bash
bun run preview
# or
npm run preview
```

## Environment Variables
This repo includes a `.env` file. If you deploy to a hosting provider, make sure you also configure the same environment variables there.

> Tip: don’t commit secrets to GitHub. If `.env` contains secrets, move them to your host’s secret manager and keep `.env` local.

## Deployment
- **Cloudflare**: this project includes `wrangler.jsonc` and Cloudflare tooling.
  - If you deploy with Cloudflare (Workers/Pages), configure environment variables in Cloudflare.
- You can also deploy the built output to other platforms that support Vite/SPA deployments.

## License
MIT (edit if you prefer a different license).