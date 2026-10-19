# Northstar — Tickerboard

A responsive crypto market dashboard with live CoinGecko market data, market overview metrics, Bitcoin history, asset sparklines, a watchlist, and price alerts.

## Run locally

Open `index.html` in a browser. Market data is fetched from the public CoinGecko API, so an internet connection is required.

## Deploy

The GitHub Actions workflow in `.github/workflows/static.yml` publishes the repository to GitHub Pages on pushes to `main`. The dashboard entry point is the root `index.html`.

If Pages has not been enabled, open **Settings → Pages** and set the build and deployment source to **GitHub Actions**.