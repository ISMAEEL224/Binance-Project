# Binance-Project
# BTC/USDT Trading Strategy (Bollinger Bands)

This Python script fetches 1 year of hourly BTC/USDT price data from Binance and performs a simple backtest using the Bollinger Bands trading strategy.

## Purpose

The goal of this project is to test a basic trading rule:  
Buy BTC when the price drops below the lower Bollinger Band, and sell it when the price goes above the upper band — to see how much profit or loss you would make.

## Features

- Uses Binance API to fetch historical data (no API key required)
- Calculates 20-period SMA and standard deviation
- Makes automatic trade decisions (BUY/SELL) based on price and bands
- Prints total trades, final capital in USDT, and trade history at the end

## Requirements

- Python 3
- `python-binance` library (install with: `pip install python-binance`)

## How to Run

```bash
python your_script_name.py
