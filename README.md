# Sales Trading Floor

**Live demo:** https://azziromulo.github.io/sales-trading-floor/

A sales dashboard designed like a stock-trading terminal. Each sales region is treated as a traded asset: its "price" is rolling 7-day revenue (in BRL thousands) and its "volume" is the number of orders. Sales leaders can read momentum, volatility and trend the same way a trader reads a chart.

## What it shows

- **Ticker tape** with every region's latest value and 7-day change (tickers SEAST, SOUTH, NEAST, CWEST, NORTH, ECOM and the SALES index)
- **Main chart** with candlestick, bar or area view, daily/weekly/monthly periods, 1M/3M/6M/1Y/all ranges and two moving averages
- **Watchlist** and an asset detail card (52-week high/low, 30-day orders, average ticket, budget attainment, year-over-year change)
- **Actual vs. budget**, year to date, by region
- **Quote board** with every KPI in one table; click a row to open it on the chart

## Data

Fictional sample data: 5 regions plus e-commerce, October 2024 to November 2026. It is the same dataset used in a companion Power BI model. No real company data is included.

## Tech

- Single static HTML file, no build step
- Charts: [TradingView Lightweight Charts](https://github.com/tradingview/lightweight-charts) 4.2.0 (Apache 2.0)
- Light and dark themes follow the system setting; layout adapts down to phone width

## Run locally

Open `index.html` in any modern browser.
