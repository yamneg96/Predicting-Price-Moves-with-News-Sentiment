# 📰💹 News Sentiment Analysis for Stock Prediction

---

## 🌟 Overview
Welcome to the **Week 1 Challenge** of the 10 Academy AI Challenge! This project explores the relationship between financial news sentiment and stock price movements for major tech stocks.

- Analyze news headlines 🗞️
- Predict stock trends 📈
- Visualize insights 📊

---

## ✨ Key Features
- 🔍 Sentiment analysis of financial headlines (TextBlob)
- 💾 Stock price data from Yahoo Finance
- 🔗 Correlation analysis between news sentiment & price returns
- 🖼️ Beautiful visualizations of sentiment-return relationships
- 📊 Technical indicators: SMA, RSI, MACD for MSFT

---

## ⚡ Quickstart
```bash
# 1. Install dependencies
pip install -r requirements.txt

# 2. Download stock data
python scripts/fetch_stock_data.py

# 3. Run technical analysis (e.g., MSFT indicators)
python scripts/technical_analysis.py

# 4. Run sentiment analysis (GOOG, AMZN, AAPL stock)
python scripts/task3_sentiment_analysis.py
```

---

## 📁 Repository Structure
```plain text
.
├── data/                       # Raw & processed data
│   ├── raw_analyst_ratings.csv    # News headlines
│   ├── *_historical_data.csv      # Stock price data
├── notebooks/                 # Visualizations & EDA
│   ├── *.png                      # Images
├── scripts/                   # Main scripts
│   ├── eda.py
│   ├── fetch_stock_data.py
│   ├── setup_nlp.py
│   ├── technical_analysis.py
│   └── task3_sentiment_analysis.py
├── requirements.txt           # Dependencies
└── README.md                  # This file
```

---

## 🏆 Key Findings
- 📈 Achieved correlation coefficient of [X] between sentiment scores and daily returns
- 🧩 Discovered [Y] pattern in sentiment distribution
- 🔥 Identified [Z] relationship between news volume and price volatility

---

## 🛠️ Technical Details
- **News Data**: Processed raw analyst ratings from `raw_analyst_ratings.csv`
- **Price Data**: Fetched historical prices using `yfinance` (2020-2021)
- **Sentiment Analysis**: Calculated polarity scores for headlines
- **Correlation**: Computed daily sentiment-return correlations
- **Technical Analysis**: Implements SMA, RSI, and MACD indicators for MSFT
- **Sentiment Analysis**: Correlates news sentiment with GOOG, AMZN, TSLA, AAPL stock returns
