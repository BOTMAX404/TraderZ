# TD Chart Terminal

A static TradingView-style chart terminal using Twelve Data and the supplied indicator logic.

## GitHub Pages

1. Create a GitHub repository.
2. Upload the contents of this folder to the repository.
3. Open **Settings -> Pages**.
4. Choose the `main` branch and `/ (root)`, or enable the included Actions workflow.
5. Open the published Pages URL.

## Use

1. Enter your own Twelve Data API key.
2. Click **Test API**.
3. Click **Load**.
4. Click **Live** for live tick streaming when your Twelve Data plan supports it.

The key is stored only in browser `localStorage`; it is not hard-coded into the repository.

## Important

GitHub Pages is static hosting, so this project does not depend on Python/server-side code. A key typed in a browser can be inspected by that browser/user. Do not commit a private/shared production key into `index.html`.

## Included

- EMA 5 / EMA 30
- ATR crossover arrows
- Swing Volume Profile
- Point of Control and HeatMap options
- ZigZag
- HH / HL / LH / LL structure
- Projected trend lines
- Optional SMA/EMA/SMMA/WMA/VWMA
- Heikin Ashi
- Multiple timeframes
