# Stock Market Indicators Pipeline 🚀

**Comprehensive Technical Analysis & Trading Signal Generation Pipeline**

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=FFD43B)](https://www.python.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF1493?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io)
[![yfinance](https://img.shields.io/badge/yfinance-007ACC?style=for-the-badge&logo=yahoo&logoColor=white)](https://github.com/ranaroussi/yfinance)

## 🌟 Overview

Advanced **Stock Momentum Pipeline** that combines **technical indicators**, **news sentiment analysis**, and **ML-based signal generation** to identify high-probability trading opportunities. Built for quantitative analysis and automated trading strategies.

**Key Features:**
- ✅ Multi-timeframe technical analysis (RSI, MACD, Bollinger Bands, Stochastic, ATR)
- ✅ Real-time CNN news sentiment integration
- ✅ ML-powered buy/sell signals with confidence scores
- ✅ Comprehensive backtesting framework
- ✅ Interactive Streamlit dashboard
- ✅ Risk management & position sizing

## 🏗️ Pipeline Architecture

```mermaid
graph TD
    A[📈 Yahoo Finance<br/>Data Ingestion] --> B[📊 Technical<br/>Indicators]
    C[📰 CNN News<br/>Sentiment] --> D[🎯 ML Signal<br/>Generation]
    B --> D
    D --> E[⚖️ Risk<br/>Management]
    E --> F[📉 Backtesting<br/>Framework]
    F --> G[📊 Streamlit<br/>Dashboard]

# 1. Clone the repository
git clone https://github.com/abinraju23/Stock_Market_Indicators_Pipeline.git
cd Stock_Market_Indicators_Pipeline

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
# venv\Scripts\activate  # Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the main pipeline
jupyter notebook PDA_Stock_Momentum_Pipeline.ipynb

# 5. Launch interactive dashboard
streamlit run dashboard.py

# Core Libraries
pandas==2.1.4 | numpy==1.26.4 | plotly==5.22.0

# Finance & Technical Analysis
yfinance==0.2.40 | ta-lib==0.4.28 | vectorbt==0.26.2

# ML & Sentiment
scikit-learn==1.5.0 | vaderSentiment==3.3.2 | transformers==4.44.0

# Visualization & Deployment
streamlit==1.38.0 | matplotlib==3.9.2 | seaborn==0.13.2
🔥 STOCK ALERT: AAPL (2026-01-15)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📊 Technicals: RSI=58.2 | MACD=Bullish | BB=Upper Break
📰 Sentiment: +0.67 (Strong Buy) 
🎯 SIGNAL: BUY (92% Confidence)
💰 Position: 1.8% ($3,420)
🛡️ Stop Loss: $148.25 (-4.2%)
🎯 Target: $165.80 (+8.7%)
⚡ ATR: $3.42 | Sharpe: 2.18
