# Trading Dashboard

A mobile-first trading performance dashboard built with React + Recharts.

## Features

- **Overview** — KPI cards, W/L streak visualiser, bounce-back stats, session summaries
- **Equity** — animated equity curve with drawdown overlay
- **Trades** — direction edge, position size scatter, full trade list with tap-to-detail drawer
- **Stats** — session thirds analysis, rolling win rate, P&L distribution, what-if slider
- **Journal** — session notes with targeted prompts, auto-generated insights, export to clipboard

## Quick Start

```bash
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173)

## Build

```bash
npm run build
npm run preview
```

## Deploy to GitHub Pages

This repo includes a GitHub Actions workflow (`.github/workflows/deploy.yml`) that automatically builds and deploys to GitHub Pages on every push to `main`.

**Setup steps:**
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select **GitHub Actions**
4. Push any commit to `main` — the site will deploy automatically

Your live URL will be: `https://<your-username>.github.io/<repo-name>/`

## Stack

- [React 18](https://react.dev)
- [Recharts](https://recharts.org)
- [Lucide React](https://lucide.dev)
- [Vite](https://vitejs.dev)
