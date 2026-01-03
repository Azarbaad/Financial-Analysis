# Stock Market Analysis Portfolio: Tech Giants (NVDA, MSFT, AAPL, AMZN)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Azarbaad/Financial-Analysis/blob/main/Stock_Analysis_Portfolio.ipynb)

## Project Description

This project performs a comprehensive financial analysis on four leading NASDAQ-listed tech stocks: **NVIDIA (NVDA)**, **Microsoft (MSFT)**, **Apple (AAPL)**, and **Amazon (AMZN)** — key players in AI, cloud computing, consumer electronics, and e-commerce.

Using real-world stock data from 2025 (fetched via `yfinance`), the analysis covers:
- Price trends and moving averages (20-day, 50-day, 200-day SMA/EMA)
- Daily returns and correlation analysis
- Modern Portfolio Theory: Efficient frontier simulation and optimal portfolio allocation (maximizing Sharpe ratio)
- Monte Carlo simulation (Geometric Brownian Motion) to forecast future price paths and assess risk

**Tools & Libraries**: Python, pandas, numpy, matplotlib, seaborn, scipy.optimize, yfinance  
**Goal**: Demonstrate practical data analysis skills for investment decision-making, risk assessment, and portfolio optimization in a real business context.

This notebook is fully interactive — click the badge above to run it in Google Colab!

## Key Insights

- **Strong Performance in 2025**: The selected stocks showed robust growth, driven by AI demand (especially NVDA) and cloud/services expansion (MSFT, AMZN). Normalized price trends highlight NVDA's outperformance.
- **High Correlations**: Returns across the four stocks are highly correlated (typically 0.7–0.9+), reflecting shared exposure to the tech sector. This limits diversification benefits within a tech-heavy portfolio.
- **Optimal Portfolio**: The mean-variance optimization suggests an allocation favoring higher-return/lower-relative-risk stocks (e.g., heavier weights on NVDA and MSFT), achieving a superior risk-adjusted return (higher Sharpe ratio) compared to equal weighting.
- **Monte Carlo Risk Assessment**: Simulations reveal significant upside potential but also volatility — e.g., wide confidence intervals for future prices, underscoring the uncertainty in tech stock forecasts.
- **Business Implication**: For investors, a diversified tech portfolio can yield strong returns but remains vulnerable to sector-wide downturns. Monte Carlo highlights the probabilistic nature of future performance.

## Screenshots


- Correlation Heatmap
  <img width="395" height="340" alt="image" src="https://github.com/user-attachments/assets/577c8a56-6b67-4664-9dd3-263270cf5c82" />

- Monte Carlo Simulation Paths
  <img width="527" height="347" alt="image" src="https://github.com/user-attachments/assets/3dbd6935-b084-4070-9874-e209581cf0e8" />

- Moving Averages for NVDA
  <img width="484" height="236" alt="image" src="https://github.com/user-attachments/assets/04c0d757-d605-45ca-9c8f-e16efa84a311" />


## How to Run
1. Open the notebook in Colab via the badge above.
2. Run all cells — data is fetched live (or use cached if offline).
3. Experiment with different time periods or add more stocks!

*Note: Past performance is not indicative of future results. This is for educational/portfolio purposes only.*
