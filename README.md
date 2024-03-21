## Automated Trading Bot Using Market Sentiment Analysis

### Abstract
This project proposes an automated trading system that utilizes market sentiment analysis derived from news articles, social media posts, and other financial information sources. The system employs natural language processing (NLP) and machine learning techniques to interpret sentiment and make trading decisions accordingly.  The strategy begins by defining parameters such as the stock symbol to trade and the risk percentage for each transaction. It then calculates the appropriate position size based on available capital and current stock price. Subsequently, it evaluates sentiment from recent news articles associated with the chosen stock. If sentiment is significantly positive or negative and exceeds a predefined threshold probability, the strategy executes corresponding buy or sell orders, incorporating predefined take-profit and stop-loss levels. Following this, the code conducts a backtest using historical data obtained from Yahoo Finance within a specified timeframe. The backtest involves simulating trading decisions based on past market conditions to assess the strategy's performance. The results of the backtest are visualized on a web page, displaying trading points over the specified period, comparing market patterns with the initialized strategy, and presenting key performance metrics in a concise "tearsheet."

### Features
- **Market Data Collection**: Gather historical and real-time market data from financial APIs and exchanges.
- **Sentiment Analysis**: Analyze sentiment from social media, news articles, and other sources using natural language processing techniques.
- **Strategy Development**: Define trading strategies based on sentiment analysis insights, technical indicators, and machine learning algorithms.
- **Backtesting**: Evaluate strategy performance using historical data to assess profitability and risk-adjusted returns.
- **Real-time Trading**: Interface with brokerage APIs to execute trades automatically based on predefined rules and parameters.
- **Risk Management**: Implement stop-loss orders, position sizing, and portfolio diversification strategies to mitigate potential losses.
- **Monitoring and Reporting**: Continuously monitor market conditions and bot performance, generating reports and alerts as needed.

### Requirements
- Operating System: Compatible with Windows, Linux, and macOS
- Programming Language: Python 3.6 or later
- Libraries: Pandas, NumPy, Scikit-learn, TensorFlow, NLTK, TextBlob, API libraries for market data
- IDE: Recommended to use VSCode or Jupyter Notebook for development
- Version Control: Git for code management and collaboration

### System Architecture
![sys_architecture drawio](https://github.com/AishreeRamesh/Project-2/assets/70213227/5024a7e9-2a2b-4274-8917-e96c2595b598)

### Flow Diagram
![flow_dia](https://github.com/AishreeRamesh/Project-2/assets/70213227/c46718a2-b865-4103-887d-98614740809e)

### Output
![image](https://github.com/AishreeRamesh/Project-2/assets/70213227/5b04acff-31b3-482e-b7d8-05ab7367affe)

![image](https://github.com/AishreeRamesh/Project-2/assets/70213227/a4567044-1951-48d8-a3ee-8ed933385bda)

![image](https://github.com/AishreeRamesh/Project-2/assets/70213227/67e0022c-f4ee-40d0-a0a9-2dac64a4d740)

![image](https://github.com/AishreeRamesh/Project-2/assets/70213227/63e25e65-cb58-4145-bc35-728d58356c5c)


### Results and Impact
The Automated Trading Bot Using Market Sentiment Analysis enhances trading efficiency, profitability, and risk management in financial markets. By integrating sentiment analysis techniques, the bot is capable of making more informed trading decisions, adapting to changing market conditions, and optimizing performance. This project contributes to the advancement of algorithmic trading research and the evolution of intelligent trading systems.

### Developed By
- [Aishree Ramesh](https://github.com/AishreeRamesh): Artificial Intelligence & NLP Researcher

### Articles Published / References
1. H. Jazayeriy and M. Daryani, "SPA Bot: Smart Price-Action Trading Bot for Cryptocurrency Market," 2021 12th International Conference on Information and Knowledge Technology (IKT), Babol, Iran, Islamic Republic of, 2021, pp. 178-182, doi: 10.1109/IKT54664.2021.9685662
2. Peng, A., Ang, S.L. and Lim, C.Y., 2022. Automated Cryptocurrency Trading Bot Implementing DRL. Pertanika Journal of Science and Technology, 30(4), p.26832705.
3. Mathur, M., Mhadalekar, S., Mhatre, S. and Mane, V., 2021. Algorithmic trading bot. In ITM Web of Conferences (Vol. 40, p. 03041). EDP Sciences.
4. M. Corletto, M. Kissel and K. Diepold, "Impact of Real-World Market Conditions on Returns of Deep Learning based Trading Strategies," 2021 International Conference on Electrical, Computer, Communications and Mechatronics Engineering (ICECCME), Mauritius, Mauritius, 2021, pp. 01-06, doi: 10.1109/ICECCME52200.2021.9590955.  
5. T. Hollis, A. Viscardi, and S. E. Yi, “A comparison of lstms and atten tion mechanisms for forecasting financial time series,” arXiv preprint arXiv:1812.07699, 2018. 
6. J. Qiu, B. Wang, and C. Zhou, “Forecasting stock prices with long-short term memory neural network based on attention mechanism,” PloS one, vol. 15, no. 1, p. e0227222, 2020.
7. S. Carta, A. Corriga, A. Ferreira, A. S. Podda, and D. R. Recupero, “A multi-layer and multi-ensemble stock trader using deep learning and deep reinforcement learning,” Applied Intelligence, vol. 51, no. 2, pp. 889–905, 2021.
8. Wang, J., Wu, X. and Zhang, C., 2005. Support vector machines based on K-means clustering for real-time business intelligence systems. International Journal of Business Intelligence and Data Mining, 1(1), pp.54-64. Google Scholar
9. W. Lv and R. Zhang, "A regression model on effective exchange rate of RMB based on Random Forest," 2011 International Conference on E-Business and E-Government (ICEE), 2011, pp. 1-3, doi: 10.1109/ICEBEG.2011.5882520.
10. Cain Evans, Konstantinos Pappas, Fatos Xhafa, Utilizing artificial neural networks and genetic algorithms to build an algo-trading model for intra-day foreign exchange speculation, Mathematical and Computer Modelling, Volume 58, Issues 5 6, 2013,
11. S. Saksonova and I. Kuzmina-Merlino, “Cryptocurrency as an investment instrument in a modern financial market,” Вестник Санкт Петербургского университета. Экономика, vol. 35, no. 2, 2019. 
12. B. Huang, Y. Huan, L. Da Xu, L. Zheng, and Z. Zou, “Automated trading systems statistical and machine learning methods and hardware implementation: a survey,” Enterp. Inf. Syst., vol. 13, no. 1, pp. 132–144, 2019.
13. M. A. H. Dempster and V. Leemans, “An automated FX trading system using adaptive reinforcement learning,” Expert Syst. Appl., vol. 30, no. 3, pp. 543 552, 2006.
