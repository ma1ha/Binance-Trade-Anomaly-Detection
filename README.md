# Binance-Trade-Anomaly-Detection
This project provides a script for detecting anomalies in trade volumes on Binance, using historical trade data for a specified trading pair. The script fetches historical trades from Binance’s public API and analyzes trade volumes, highlighting any trades that fall outside a given threshold (based on standard deviation).
#Features
* Fetch Historical Trades: Retrieves the most recent trades for a given symbol (e.g., BTCUSDT) from the Binance API.
* Anomaly Detection: Identifies trades with volumes significantly higher or lower than the average trade volume using a customizable threshold multiplier.
* Time and Volume Output: Displays the timestamp and trade volume for each detected anomaly.
# Requirements
Python 3.x
requests: For making HTTP requests to the Binance API.
numpy: For calculating statistical data like mean and standard deviation.
