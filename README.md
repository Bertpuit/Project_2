# S&P 500 Trading Strategy Optimization Project

As a collective passionate about financial markets, we recognize the S&P 500 as a key barometer of the performance of 500 major companies listed on stock exchanges in the United States. Our project aims to explore and refine trading strategies that leverage this index, enhancing our understanding and effectiveness in market engagement.

## In-depth Exploration of Key Points

### Simple Moving Averages (SMA)

- We started by analyzing the S&P 500 using SMAs with varied time windows. SMAs smooth out price data by calculating the average price of the stock over a specific number of days, thus providing us with insights into the market trend.
- Our approach involved iterating through combinations of short and long SMA periods, calculating these directly within a loop, and then applying the AdaBoost classifier to assess the effectiveness of each combination.

### Relative Strength Index (RSI)

- The RSI is a momentum oscillator that measures the speed and change of price movements. It oscillates between zero and 100 and is typically used to identify overbought or oversold conditions in a stock.
- In our project, we calculated the RSI for the S&P 500 and went further to compute the slope of the RSI over recent periods. This slope gives us additional insight into the momentum behind the index's movements.

### AdaBoost Classifier

- We chose the AdaBoost classifier for its effectiveness in enhancing the performance of decision trees. By combining multiple weak classifiers to form a strong classifier, AdaBoost helps in increasing the accuracy of our predictions.
- Our application of cross-validation and AdaBoost enabled us to filter through the myriad of SMA combinations, focusing on those that offer the highest accuracy.
