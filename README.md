# Northstar — Market Intelligence

A standalone, responsive crypto market dashboard with live CoinGecko market data, market overview metrics, a Bitcoin history chart, asset sparklines, a watchlist, and price alerts.

## Run locally

Open `index.html` in a browser. Market data is fetched from the public CoinGecko API, so an internet connection is required.

## Deploy

The GitHub Actions workflow in `.github/workflows/deploy-pages.yml` publishes the repository root to GitHub Pages on pushes to `main`.

If Pages has not been enabled for this repository yet, open **Settings → Pages** and set the build and deployment source to **GitHub Actions**.
