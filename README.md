# python-ML-and-finance-notes

This repo is a space for me to practice both machine learning and financial data analysis in Python. It is not meant to be a polished project or provide a complete analysis of a given topic, it is just a place to work through techniques with real data and get comfortable with the relevant libraries. Each notebook has been cleaned up and documented so it is readable on its own.

## Finance Notebooks

**credit.ipynb**:
A technical and fundamental analysis of JPMorgan Chase (JPM). Pulls daily price history with `yfinance` and looks at moving averages and daily returns, then pulls JPM's annual cash flow statement with `financetoolkit` and walks through each major line item (net income, working capital, operating cash flow, capital expenditures, free cash flow, and so on), explaining what each one means and what it typically signals about the company's financial health.

**sma_ema.ipynb**:
A comparison of the simple moving average (SMA) and exponential moving average (EMA) on the S&P 500 and S&P MidCap 400 indices. Covers how each indicator is calculated, how they differ in how they weight recent prices, and how to interpret the cumulative growth of the EMA-smoothed price series over time.

## Machine Learning Notebooks
Will update. 

## Setup

Both notebooks pull live data, so an internet connection is required to run them. `credit.ipynb` also needs a `financetoolkit` API key, which should be set as an environment variable rather than hardcoded.
