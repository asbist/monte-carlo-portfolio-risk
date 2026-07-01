# Monte Carlo Portfolio Risk & Scenario Analysis
This project builds a Python-based portfolio risk analytics framework with Monte Carlo Simulation, downside risk metrics, drawdown analysis, stress testing, historical stress calibration, and volatility sensitivity analysis. The aim of this project is to examine how a multi-asset portfolio may perform under normal market conditions, historical stress events and higher-volatility markets.

## Project Overview
This notebook analyses a diversified portfolio with S&P 500 exposure, Nasdaq-100 growth equity exposure, long-duration US government bonds, gold, and the US dollar. Historical market data is used to estimate daily returns, covariance relationships, volatility, and downside risk. The project then turns this basic Monte-Carlo Simulation into a broader risk-framework by implementing:

- Value at Risk
- Expected Shortfall
- Drawdown Analysis
- Analyst-defined stress testing
- Historically calibrated stress testing
- Volatility sensitivity analysis

## Key features
- Downloads historical asset price data using 'yfinance'
- Calculates daily portfolio returns and annualised risk-return statistics
- Runs Monte Carlo simulations for one-year portfolio outcomes
- Estimates 95% VaR and Expected Shortfall
- Visualises forecast cones and simulated return distributions
- Measures historical and simulated drawdowns
- Tests portfolio performance under analyst-defined market shocks
- Applies historical stress periods to test portfolio resilience
- Analyses how downside risk changes under-higher volatility regimes

## Technologies Used
- Python
- pandas
- NumPy
- matplotlib
- yfinance
- Jupyter Notebook

## Key Finance Concepts
This project showcases several important market and risk-management concepts:

- Monte Carlo Simulation
- Portfolio Diversification
- Covariance and correlation
- Value at Risk
- Volatility
- Expected Shortfall
- Tail Risk
- Drawdown
- Stress Testing
- Historical Calibration
- Diversification breakdown
- Volatility Regimes

## Main Findings
This project shows how a multi-asset portfolio can be assed across normal, stressed, and higher volatility market regimes.

The results highlight three key themes:
-Average returns don't fully capture downside risk
-Diversification can weaken during inflation and rates shocks, especially when long-duration bonds and equities fall at the same time.
-Higher volatility increases tail risk and drawdown exposure, even when expected returns are held constant.

Overall, this analysis demonstrates how Monte Carlo simulation, stress testing, drawdown analysis, and volatility sensitivity can be used to build a practical portfolio risk framework.

## How to Run

Install the required packages:

```bash
pip install pandas numpy matplotlib yfinance jupyter

