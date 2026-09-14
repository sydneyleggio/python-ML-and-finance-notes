# python-ML-and-finance-notes

This repo is a space for me to practice both machine learning and financial data analysis in Python. It is not meant to be a polished project or provide a complete analysis of a given topic, it is just a place to work through techniques with real data and get comfortable with the relevant libraries. Each notebook has been cleaned up and documented so it is readable on its own.

## Finance Notebooks

**credit.ipynb**:
A technical and fundamental analysis of JPMorgan Chase (JPM). Pulls daily price history with `yfinance` and looks at moving averages and daily returns, then pulls JPM's annual cash flow statement with `financetoolkit` and walks through each major line item (net income, working capital, operating cash flow, capital expenditures, free cash flow, and so on), explaining what each one means and what it typically signals about the company's financial health.

**sma_ema.ipynb**:
A comparison of the simple moving average (SMA) and exponential moving average (EMA) on the S&P 500 and S&P MidCap 400 indices. Covers how each indicator is calculated, how they differ in how they weight recent prices, and how to interpret the cumulative growth of the EMA-smoothed price series over time.

## Machine Learning Notebooks

**advanced.ipynb**:
Advanced applications of Python, including problems like the quantum harmonic oscillator, polynomials, and Monte Carlo simulations.

**basics.ipynb**:
Python basics including starter math and eigenvalue calculations. 

**gradientdescent.ipynb**:
Explores linear and logistic regression via gradient descent.

**logistic_knn.ipynb**:
Explores regression vs. classification intricacies using logistic regression and k-Nearest Neighbors approaches.

**machine_learning.ipynb**:
Evaluates overfitting, underfitting, and a good fit of a ML model. 

**pandas.ipynb**:
Explores a Titanic passenger dataset and focuses on data visualization using `pandas`.

**pca.ipynb**:
Principal Component Analysis applied to a Gaussian cloud, ovarian cancer data, and then human faces.

**regression.ipynb**:
Evaluates regression model fit for rental prices. 

**scikit_pytorch.ipynb**:
Simple introduction to data exploration and plotting using `scikit-learn` and `PyTorch`. 

**svd.ipynb**:
Singular Value Decomposition shown using an image of dogs. Explores low-rank approximation and assembling an image using one layer at a time. 

**svd_2.ipynb**: 
Singular Value Decomposition shown using the same image of dogs, but this notebook explores modes, snapshots, and the pseudo-inverse.

## Setup

Both finance notebooks pull live data, so an internet connection is required to run them. `credit.ipynb` also needs a `financetoolkit` API key, which should be set as an environment variable rather than hardcoded. The data and photos used for the ML notebooks are provided in the same folder. 
