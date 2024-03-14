# AUTOMATED TRADING BOT USING MARKET SENTIMENT ANALYSIS

## Overview
This project proposes an automated trading system that utilizes market sentiment analysis derived from news articles, social media posts, and other financial information sources. The system employs natural language processing (NLP) and machine learning techniques to interpret sentiment and make trading decisions accordingly.  The strategy begins by defining parameters such as the stock symbol to trade and the risk percentage for each transaction. It then calculates the appropriate position size based on available capital and current stock price. Subsequently, it evaluates sentiment from recent news articles associated with the chosen stock. If sentiment is significantly positive or negative and exceeds a predefined threshold probability, the strategy executes corresponding buy or sell orders, incorporating predefined take-profit and stop-loss levels. Following this, the code conducts a backtest using historical data obtained from Yahoo Finance within a specified timeframe. The backtest involves simulating trading decisions based on past market conditions to assess the strategy's performance. The results of the backtest are visualized on a web page, displaying trading points over the specified period, comparing market patterns with the initialized strategy, and presenting key performance metrics in a concise "tearsheet."

## Features
- **Market Data Collection**: Gather historical and real-time market data from financial APIs and exchanges.
- **Sentiment Analysis**: Analyze sentiment from social media, news articles, and other sources using natural language processing techniques.
- **Strategy Development**: Define trading strategies based on sentiment analysis insights, technical indicators, and machine learning algorithms.
- **Backtesting**: Evaluate strategy performance using historical data to assess profitability and risk-adjusted returns.
- **Real-time Trading**: Interface with brokerage APIs to execute trades automatically based on predefined rules and parameters.
- **Risk Management**: Implement stop-loss orders, position sizing, and portfolio diversification strategies to mitigate potential losses.
- **Monitoring and Reporting**: Continuously monitor market conditions and bot performance, generating reports and alerts as needed.

## Architecture Diagram
![sys_architecture drawio](https://github.com/AishreeRamesh/Project-2/assets/70213227/5024a7e9-2a2b-4274-8917-e96c2595b598)

## Flow Diagram
![flow_dia](https://github.com/AishreeRamesh/Project-2/assets/70213227/c46718a2-b865-4103-887d-98614740809e)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/AishreeRamesh/Project-2.git
   cd Project-2
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up API keys:
   - Obtain API keys from your preferred financial data provider and brokerage platform.
   - Add API keys to the configuration file (`config.yaml`).

## Usage
1. Configure trading parameters in the `config.yaml` file, including:
   - Trading strategy settings
   - Risk management parameters
   - API keys and connection settings
2. Run the bot:
   ```bash
   python tradingbot.py
   ```
3. Monitor bot performance and adjust parameters as needed based on real-time market conditions.

## Developed By
- [Aishree Ramesh](https://github.com/AishreeRamesh): Artificial Intelligence & NLP Researcher

## Contributing
Contributions are welcome! Please fork the repository and submit pull requests for any enhancements or bug fixes.
