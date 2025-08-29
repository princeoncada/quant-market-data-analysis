# Quant Project — Market Data Loader & Returns Analysis

**Goal**: Pull market data and study statistical properties of returns (log-returns, rolling volatility, correlations, and distributions) using Google Colab.

**Data**: Yahoo Finance | **Period**: 2018-01-01 → 2025-01-01
**Assets**: AAPL, MSFT, GOOG, TSLA, SPY

## Outputs
- **Research Paper (PDF)**: `docs/statistical_properties.pdf`
- **Notebooks**: `notebooks/market_data_analysis.ipynb`
- **Charts**: `docs/charts`
- **Prices CSV**: `docs/`

## Key Charts
- `spy_price.png` — SPY Price levels
- `aapl_daily_returns.png` — AAPL Daily Returns
- `rolling_30_vol.png` — Rolling Annualized Volatility
- `rolling_60_corr_aapl_msft.png` — AAPL vs MSFT Rolling Correlation
- `corr_matrix.png` — Cross-asset Correlation Matrix
- `aapl_hist_returns.png` — Distribution of returns
