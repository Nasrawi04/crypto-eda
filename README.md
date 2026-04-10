# 📈 Cryptocurrency Market — Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![yfinance](https://img.shields.io/badge/yfinance-Market%20Data-green)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 📌 Overview

An advanced Exploratory Data Analysis (EDA) project analyzing 11 major cryptocurrencies across 4 categories over a 5-year period (2021–2026).

The project goes beyond basic price charting to answer deeper analytical questions:

> **Which coins offer the best risk-adjusted returns? How did the 2022 bear market impact each category? Does diversifying across crypto assets actually reduce risk?**

---

## 🪙 Coins Analyzed

| Category | Coins |
|---|---|
| 🔵 Large Cap | BTC, ETH, BNB |
| 🟣 Layer-1 / DeFi | SOL, AVAX, MATIC |
| 🟠 DeFi Infrastructure | LINK |
| 🟡 Mid Cap | XRP, ADA, LTC |
| 🟢 Meme Coin | DOGE |

---

## 📊 Key Findings

| Metric | Result |
|---|---|
| Best 5-Year Return | **SOL +210.3%** |
| Worst 5-Year Return | **ADA -79.2%** |
| Best Sharpe Ratio | **SOL (0.70)** |
| Worst Sharpe Ratio | **LTC (-0.01)** |
| Most Volatile | **DOGE (1.17 annualized)** |
| Least Volatile | **BTC (0.56 annualized)** |
| Worst Max Drawdown | **SOL -96.3%** |
| Best Max Drawdown | **BNB -70.8%** |
| $1,000 in SOL → | **$3,103** |
| $1,000 Equal Weight → | **$966** (dragged down by underperformers) |
| Highest BTC Correlation | **ETH (0.83)** |

---

## 💡 Key Business Insights

1. **SOL dominates** — best total return (210%), best Sharpe (0.70), and highest $1,000 growth ($3,103) despite having the worst max drawdown (-96.3%)
2. **No coin achieved a Sharpe Ratio above 1.0** — confirming that crypto delivers high returns at the cost of extreme risk across the board
3. **Equal weight diversification underperformed** — returning only $966 on $1,000, pulled down heavily by ADA, LTC, LINK, and AVAX
4. **Legacy mid-caps (LTC, ADA) are the biggest losers** — both down ~79% over 5 years as capital rotated to newer ecosystems
5. **BNB showed the best drawdown protection (-70.8%)** — exchange utility token proved more resilient than pure L1 competitors
6. **All coins are highly correlated with BTC** — crypto does not provide true portfolio diversification; all assets move together in a crisis
7. **The 2022 bear market was catastrophic** — every single coin lost 70–96% from peak, with no safe haven in the asset class
8. **SOL and AVAX's RSI fired bullish signals earlier than BTC** in the 2024 recovery, confirming altcoin leadership in that cycle

---

## 🗂️ Project Structure

```
crypto-eda/
│
├── crypto_eda.ipynb       # Main analysis notebook (16 sections)
└── README.md              # Project documentation
```

---

## 🔍 Analysis Sections

1. **Setup** — Libraries and configuration
2. **Data Fetching** — Live 5-year price data via yfinance API
3. **Data Quality** — Missing values, date ranges, row counts
4. **Price History** — Normalized price charts for all 11 coins
5. **Daily Returns** — Distribution analysis with skewness and kurtosis
6. **Volatility Analysis** — 30-day rolling annualized volatility
7. **Moving Averages** — 7, 30, and 90-day MA trend analysis
8. **Bollinger Bands** — Volatility bands and squeeze detection
9. **RSI** — Overbought/oversold signals for last 12 months
10. **Correlation Matrix** — Pairwise and BTC correlation analysis
11. **Monthly Returns Heatmap** — Seasonality patterns per coin
12. **Drawdown Analysis** — Fall from peak for every coin
13. **Sharpe Ratio** — Risk-adjusted return ranking
14. **Total Returns** — 5-year return comparison
15. **Portfolio Simulation** — $1,000 equal weight vs individual coins
16. **Key Insights** — Complete 10-section analysis report with coin-by-coin breakdown

---

## 🛠️ Tools & Skills

- **Python** — pandas, numpy, matplotlib, seaborn, yfinance
- **Time-Series Analysis** — multi-year price trends and seasonality
- **Risk Modeling** — Sharpe Ratio, annualized volatility, max drawdown
- **Technical Indicators** — RSI, Bollinger Bands, moving averages
- **Portfolio Analysis** — equal weight simulation, correlation risk
- **Financial Storytelling** — translating quantitative findings into actionable insights

---

## 🚀 How to Run

1. Clone the repo
   ```bash
   git clone https://github.com/Nasrawi04/crypto-eda.git
   ```
2. Open `crypto_eda.ipynb` in [Google Colab](https://colab.research.google.com) or Jupyter
3. Run all cells — data is fetched automatically via yfinance, no CSV needed

---

## 📁 Data Source

- **Provider:** Yahoo Finance via [yfinance](https://pypi.org/project/yfinance/) Python library
- **Period:** April 2021 — April 2026
- **Interval:** Daily closing prices
- **Coins:** BTC, ETH, BNB, SOL, XRP, ADA, LTC, DOGE, AVAX, MATIC, LINK

---

## 👤 Author

**Nasser**
Student @ Rochester Institute of Technology — Dubai
[LinkedIn](https://linkedin.com/in/yourprofile) • [GitHub](https://github.com/Nasrawi04)
