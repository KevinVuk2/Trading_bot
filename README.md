#  Forex Algorithmic Trading Bot & Strategy Research

This project combines algorithmic trading, data analysis, and technical research into a complete workflow for building and deploying trading strategies. It includes a live trading bot that runs on the OANDA v3 API, along with several Jupyter notebooks for exploring, testing, and validating technical indicators.

🔍 Project Overview

The system is designed to answer one question:

Can we research trading strategies, validate them with data, and deploy them into an automated Forex trading bot?

To achieve this, the project includes:

✔ Live Trading Bot

Fetches real-time candles from OANDA

Applies technical indicators (Bollinger Bands-based breakout strategy)

Generates BUY/SELL signals

Calculates position sizing based on risk

Places trades automatically with SL/TP

Logs all decisions and executions

✔ Strategy Research Suite

A set of Jupyter notebooks used for systematic exploration:

Guru_2_MACD_EMA100.ipynb – MACD + EMA trend filters

Guru_Tester.ipynb – general strategy testing framework

Indicators.ipynb – indicator calculations (MA, EMA, MACD, Bollinger Bands)

MA_Cross_An.ipynb, MA_Test.ipynb – moving average crossover exploration

plotting_candles.ipynb – interactive candlestick visualization

These notebooks help evaluate performance, test ideas quickly, and compare results across pairs.

📊 Precomputed Strategy Results

Backtesting outputs are stored as .pkl files (e.g., macd_ema_res_GBP_JPY.pkl).
Each file contains:

Strategy returns

Trend classifications

MACD/EMA signals

Candle direction patterns

Win/loss statistics

These allow rapid experimentation without re-running full backtests.

📈 Interactive Charting (Plotly)

The included plotting.py module creates:

High-resolution candlestick charts

Indicator overlays (MA, EMA, MACD, Bollinger Bands)

Secondary-axis support

Dark-themed visualizations

Useful for visually validating patterns and inspecting price behavior.
