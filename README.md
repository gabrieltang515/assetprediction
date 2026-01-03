# SPY Forward Return Prediction & Trading Strategy

## Overview
This project predicts SPY's forward 5-day returns using machine learning and evaluates two trading strategies.

## Setup Instructions

1. **Install Python dependencies:**
   pip install -r requirements.txt
   2. **Open the notebook:**
   jupyter notebook notebooks/q1_spy_regression.ipynb
      Or use JupyterLab:
   jupyter lab notebooks/q1_spy_regression.ipynb
   3. **Run all cells:**
   - The notebook will automatically download data from Yahoo Finance
   - No API keys or additional setup required
   - All data is fetched on-the-fly

## Requirements
- Python 3.8+
- Internet connection (for downloading market data via yfinance)

## Notes
- Data is downloaded from Yahoo Finance, so results may vary slightly based on when you run it
- All predictions are out-of-sample using walk-forward validation
- Transaction costs (5 bps) are included in strategy returns
