# TD Chart Terminal — GitHub Pages

Static TradingView-style chart terminal using Twelve Data.

## Deploy
1. Create a GitHub repository.
2. Upload everything in this folder to the `main` branch.
3. Open **Settings → Pages** and publish from `main` / root.
4. Open the published site, enter your own Twelve Data API key, press **Test API**, then **Load**.

The page uses Twelve Data query-string authentication first, with an Authorization-header fallback. The query-string format is documented by Twelve Data and is suitable for a static browser app.

The API key is stored locally in the browser and is not written into the repository. Do not hard-code a private/shared key in `index.html`.

### Important
Some symbols/data intervals require the corresponding Twelve Data market-data permission. The **Test API** button checks both `/quote` and `/time_series`, so it can distinguish an authentication problem from missing candle-data access.
