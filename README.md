# CapMan-Oyj-DCF-Valuation-Monte-Carlo-Simulation-Comparable-Companies-Capital-Structure
CapMan Oyj – Valuation Analysis
**DCF Valuation | Monte Carlo Simulation | Comparable Companies | Capital Structure**

Independent valuation project of **CapMan Oyj (NASDAQ Helsinki: CAPMAN)**.  
The model combines fundamental forecasting, a sum-of-the-parts DCF valuation, trading comparables and Monte Carlo simulation.

## Project Overview

The valuation separates CapMan's **operating asset management business** from its balance-sheet investment portfolio.

The operating business is valued using an **FCFF-based DCF**, while CapMan's investment portfolio is added separately at **NAV / fair value** in the equity value bridge.

The model includes:

- **AUM Forecasting** – historical and projected assets under management by investment area
- **Operating DCF** – revenue, operating EBIT, FCFF and terminal value
- **Portfolio NAV** – balance-sheet investments valued separately from operating earnings
- **Capital Structure** – CAPM, cost of equity, cost of debt and WACC
- **Comparable Companies Analysis** – FY2025A EV/Revenue, EV/EBIT and P/E benchmarking
- **Monte Carlo Simulation** – fair value distribution based on simulated WACC and terminal growth assumptions
- **Historical Financial Statements** – income statement, balance sheet and cash flow statement
- **Market Data Analysis** – share price history, ROE, volatility and beta

## Comparable Companies

Peer group:

- eQ Oyj
- Evli Oyj
- Taaleri Oyj
- United Bankers Oyj
- Titanium Oyj

The comparable analysis uses **FY2025A reported financials** to maintain consistency across the peer group.

## Python / Data

Python and `yfinance` are used for supporting market-data analysis, including:

- Historical CapMan share prices
- Beta estimation
- 60-day and 252-day annualised volatility
- Historical ROE
- Market multiples and financial metrics
- Excel data export and visualisation
