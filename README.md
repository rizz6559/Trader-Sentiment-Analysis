# Trader Performance vs Market Sentiment Analysis

## Objective
This project analyzes how Bitcoin market sentiment (Fear vs Greed) influences trader behavior on Hyperliquid.

## Dataset
1. Bitcoin Fear & Greed Index
2. Historical trader execution data

## Methodology
- Data cleaning and preprocessing
- Timestamp conversion and dataset alignment
- Exploratory data analysis
- Visualization of trader behavior
- PnL proxy analysis
- Trader segmentation based on trade size

## Key Insights
- Trading activity varies across different sentiment phases.
- Traders tend to place larger trades during Greed sentiment.
- Fear sentiment shows relatively higher short-selling behavior.
- A small number of traders dominate overall trading activity.

## Strategy Ideas
1. Reduce leverage and trade size during Fear sentiment due to higher volatility.
2. During Greed sentiment, momentum strategies may perform better due to increased buying pressure.
3. Monitoring sentiment alongside trader behavior may help identify market shifts.

## Files
- `Trader_Sentiment_Analysis.ipynb` – Full analysis notebook
- `historical_data.csv` – Trader dataset
- `fear_greed_index.csv` – Market sentiment dataset
