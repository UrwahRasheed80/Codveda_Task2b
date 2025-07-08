# Time Series Analysis on Apple (AAPL) Stock Data

This project is a beginner-friendly time series analysis where I focused on **Apple's stock price (AAPL)** to understand trends and patterns over time.

---

## What I Did

- Filtered the data for AAPL from a dataset with many stock symbols
- Plotted the **closing prices** over time
- Broke the time series into:
  - **Trend**: The general direction over time
  - **Seasonality**: Repeating patterns
  - **Residual**: Random ups and downs
- Applied a **30-day moving average** to smooth the line and make trends easier to see

---

## Dataset Info

The data includes:
- `symbol` – stock symbol (like AAPL)
- `open`, `high`, `low`, `close`, `volume`
- `date` – already set as the index

I used only AAPL to focus on one company:
```python
aapl = df[df['symbol'] == 'AAPL']

#Python #TimeSeriesAnalysis #StockMarket #DataScience #AAPL #BeginnerProjects
