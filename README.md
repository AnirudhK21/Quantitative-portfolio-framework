# Quantitative Portfolio Analytics and Risk Management Framework

# Overview

This project develops an end-to-end quantitative investment research framework using Python. The framework combines portfolio construction, risk analytics, volatility modelling, regime detection, and portfolio optimization to evaluate investment performance and risk across a diversified equity portfolio.

 Key Features

# Portfolio Construction

* Equal Weight Portfolio
* Minimum Variance Portfolio
* Risk Parity Portfolio
* Maximum Sharpe Portfolio

# Risk Analytics

* CAGR
* Volatility
* Sharpe Ratio
* Sortino Ratio
* Calmar Ratio
* Maximum Drawdown
* Value at Risk (VaR)
* Conditional Value at Risk (CVaR)

# Volatility Modelling

* Rolling Volatility
* Rolling Sharpe Ratio
* GARCH(1,1) Conditional Volatility
* Volatility Forecasting

# Regime Detection

* Hidden Markov Model (HMM)
* Market Regime Classification
* Regime Statistics

# Portfolio Optimization

* Monte Carlo Portfolio Simulation
* Efficient Frontier
* Maximum Sharpe Portfolio Optimization

# Results

| Metric           |   Value |
| ---------------- | ------: |
| CAGR             |  25.75% |
| Volatility       |  21.53% |
| Sharpe Ratio     |    1.17 |
| Sortino Ratio    |    1.08 |
| Maximum Drawdown | -42.01% |

# Efficient Frontier

![Efficient Frontier](figures/efficient_frontier.png)

# HMM Regime Detection

![HMM Regimes](figures/hmm_regimes.png)

# Rolling Volatility vs GARCH

![Volatility](figures/rolling_vs_garch.png)

# Correlation Analysis

![Correlation](figures/correlation_heatmap.png)

# Portfolio Equity Curve

![Equity Curve](figures/equity_curve.png)

# Monthly Returns Heatmap

![Monthly Returns](figures/monthly_returns_heatmap.png)

# Technologies

* Python
* Pandas
* NumPy
* SciPy
* Matplotlib
* ARCH
* HMMlearn
* yFinance

# Future Improvements

* Interactive Dashboard
* Multi-Asset Portfolio Support
* Factor Models
* Regime-Aware Portfolio Allocation
* Live Market Data Integration
