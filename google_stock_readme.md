# 📈 Google Stock Price Analysis (2015–2024)

This project presents an exploratory data analysis (EDA) and visualization of **Alphabet Inc. (GOOGL)** daily stock prices spanning nearly a decade — from 2015 to 2024. The dataset offers insights into stock price trends, volatility, volume shifts, and return behavior.

---

## 📊 Key Highlights from the EDA

### 🚀 Remarkable Growth Trajectory  
The **daily close price chart** reflects GOOGL’s consistent and substantial long-term growth. The acceleration of stock price in recent years reinforces strong market confidence and the company’s robust performance.

---

### 🔄 Shifting Trading Volumes  
There is a **drastic spike in trading volume starting mid-2022**, continuing into 2023 and 2024, with multiple peaks reaching record highs.

#### 📌 Main Driver: Alphabet’s 20-for-1 Stock Split
- **📅 Date:** July 15, 2022  
- **🔁 What Happened:**  
  - Investors received 20 shares for every 1 held.  
  - Stock price dropped significantly (e.g., ~$2,200 to ~$110).  
- **📊 Volume Impact:**  
  - Many datasets **do not adjust volume** post-split.  
  - Hence, the charts show a **visual surge in volume**, due to the multiplication of shares — **not necessarily an increase in total trading value**.

> ⚠️ When analyzing volume after July 2022, consider the split effect to avoid misinterpreting market interest.

---

### 🤭 Price Distribution Patterns  
The histogram of **close prices** reveals shifting price regimes — periods where prices cluster in specific ranges — suggesting different **growth phases** across the 10-year timeline.

---

### 📈 Moving Averages & Trend Signals  
The addition of **50-day and 200-day moving averages** highlights the stock’s long-term bullish trend. GOOGL has consistently traded **above its long-term averages**, signaling strong investor confidence.

---

### 📉 Daily Return Behavior  
The distribution of **daily returns** is tightly centered around zero, with **occasional large spikes** both positive and negative.  
- **Rolling volatility windows** show periods of turbulence, often corresponding to broader economic shifts or company events.

---

### 📌 Correlation Matrix  
There is a **near-perfect correlation (≈1.0)** among Open, High, Low, and Close prices — as expected in daily stock data.  
Volume, while positively correlated, shows a **moderate relationship**, suggesting partial dependency between price action and trading activity.

---

## 📂 Dataset Used
- **Name:** GoogleStockPrices.csv  
- **Source:** Kaggle  
- **Fields:** Date, Open, High, Low, Close, Volume

---

## 🛠️ Tools & Libraries
- `pandas`, `matplotlib`, `seaborn`
- Python 3.9+
- Jupyter Notebook

---

## 📌 Next Steps (Forecasting Models)
This EDA lays the foundation for building predictive models using:
- **ARIMA** – for time series forecasting  
- **Prophet** – for trend and seasonality-aware predictions  
- **LSTM** – for deep learning-based sequence prediction

---

