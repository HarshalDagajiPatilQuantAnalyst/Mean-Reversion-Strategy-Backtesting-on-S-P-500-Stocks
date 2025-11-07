# Mean Reversion Strategy Backtesting on S&P 500 Stocks

##  Project Overview
This project implements a quantitative mean reversion trading strategy applied to S&P 500 stocks. It uses historical price data, statistical tests, and a robust backtesting engine to evaluate the performance of the strategy over a 5-year period.

##  Features
- Fetches historical data using `yfinance`
- Cleans and preprocesses stock data
- Applies ADF test and Hurst Exponent for stationarity
- Generates trading signals using z-score and Bollinger Bands
- Backtests with transaction costs, slippage, and position sizing
- Calculates performance metrics: Sharpe Ratio, CAGR, Max Drawdown, Win Rate
- Visualizes equity curve, drawdowns, and trade signals
- Logs trades in a structured CSV format

##  Strategy Description
The strategy identifies mean-reverting behavior in stock prices. When the z-score of a stock's price deviates significantly from its mean, the model enters a position expecting a reversion. Entry and exit signals are based on z-score thresholds.

##  Installation
```bash
pip install yfinance pandas numpy matplotlib plotly statsmodels
```

##  Usage Instructions
1. Clone the repository:
```bash
git clone https://github.com/yourusername/mean-reversion-backtest.git
cd mean-reversion-backtest
```
2. Run the Jupyter Notebook or Python script:
```bash
jupyter notebook backtest_mean_reversion.ipynb
```

## 📁 Project Structure
```
├── backtest_mean_reversion.ipynb   # Main notebook
├── trade_log.csv                   # Logged trades
├── results/                        # Plots and performance metrics
├── README.md                       # Project documentation
```

##  Results Summary
- Positive Sharpe Ratio
- Controlled drawdowns
- Stable equity curve
- Transparent trade logs

##  Contact
**Harshal Patil**  
Quantitative Researcher | Derivatives Pricing  
📍 Mumbai, Maharashtra  
📧 hp952027@gmail.com 
🔗 [LinkedIn](https://www.linkedin.com/in/harshal-patil-a10644172/) |
