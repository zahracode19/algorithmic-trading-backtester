# Algorithmic Trading Backtester

## Overview
A Python-based backtesting engine that tests a Moving Average Crossover 
strategy on Apple (AAPL) stock data from 2020 to 2024.

## Tools Used
- Python
- Jupyter Notebook
- yfinance
- Pandas
- NumPy
- Matplotlib

## Strategy
Moving Average Crossover:
- BUY when 50-day MA crosses above 200-day MA (Golden Cross)
- SELL when 50-day MA crosses below 200-day MA (Death Cross)

## Key Concepts Covered
- Historical stock data collection
- Daily returns and annualised volatility
- Moving average calculation
- Signal and position generation
- Buy/Sell signal visualisation

## How to Run
1. Install requirements: pip install yfinance pandas numpy matplotlib
2. Open algorithmic_trading_backtester.ipynb in Jupyter Notebook
3. Run all cells from top to bottom
