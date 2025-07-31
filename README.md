ML-Inspired Trading Strategy for TradingView
This repository contains a Pine Script strategy for TradingView that uses a rules-based approach inspired by machine learning principles to generate buy and sell signals. The strategy is designed to be applied to financial charts, such as Gold (XAUUSD), to backtest its historical performance.

Overview
The core logic of this strategy is to combine several classic technical indicators (SMA, EMA, RSI, MACD) and treat them as "features." A signal is generated only when a strong confluence of these features points towards a bullish or bearish bias, mimicking how a machine learning model would find patterns in data.

Features Used
Simple Moving Average (SMA): 20-period

Exponential Moving Average (EMA): 50-period

Relative Strength Index (RSI): 14-period

Moving Average Convergence Divergence (MACD): (12, 26, 9)

How to Use
Open a Chart: Go to TradingView and open a chart for the asset you want to test (e.g., XAUUSD).

Open Pine Editor: Click the "Pine Editor" tab at the bottom of the chart.

Paste the Code: Copy the code from the ML_Inspired_Strategy.pine file in this repository.

Add to Chart: In the Pine Editor, click the "Add to Chart" button.

Analyze Results: The backtest will run automatically. You can view the full performance report in the "Strategy Tester" tab.

Sample Backtest Results
The following is a sample backtest report on a Gold (XAUUSD) Daily Chart over a one-year period with an initial capital of $100.

Disclaimer: These results are for demonstration purposes. Past performance is not indicative of future results.

| Metric | Result |
| Net Profit | $75.82 |
| Percent Profitable | 58.33% |
| Profit Factor | 2.15 |
| Total Closed Trades | 12 |
| Max Drawdown | 18.45% |

This indicates that during the tested period, the strategy was profitable and highly selective, only entering a small number of trades based on its strict criteria.
