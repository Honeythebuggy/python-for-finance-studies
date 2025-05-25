# 📈 Python for Finance Studies

Jupyter notebooks from *Python for Finance* by Yves Hilpisch — rebuilt with my notes, signals, and charting experiments.

##Project 1: SMA Crossover Strategy (SPY)

This project implements a simple technical trading strategy using **Simple Moving Averages (SMA)**:

- Uses daily data of the **SPY ETF** (tracks the S&P 500)
- Computes:
  - 20-day SMA (short-term)
  - 50-day SMA (long-term)
- Buy Signal: when SMA20 **crosses above** SMA50
- Sell Signal: when SMA20 **crosses below** SMA50
- Plots:
  - Price line
  - Both SMAs
  - (Next: Buy/Sell arrows, portfolio simulation)
### 🔗 Notebook

🧾 [`chapter1-sma-crossover.ipynb`](chapter1-sma-crossover.ipynb)

---

