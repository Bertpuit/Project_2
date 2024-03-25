# S&P 500 Trading Strategy Optimization Project

As a collective passionate about financial markets, we recognize the S&P 500 as a key barometer of the performance of 500 major companies listed on stock exchanges in the United States. Our project aims to explore and refine trading strategies that leverage this index, enhancing our understanding and effectiveness in market engagement.

[Check out our Main Python File!](https://github.com/jancichocki/Project_2/blob/main/main.ipynb)

## The Significance of the S&P 500

### A Comprehensive Market Snapshot
The S&P 500 provides a broad and diverse look at the U.S. economy through its inclusion of companies from all sectors. This diversity makes it an invaluable tool for gauging overall market sentiment and economic health.

### Benchmark for Performance
For individual investors and financial professionals alike, the S&P 500 serves as a critical benchmark. Assessing an investment's performance against this index helps in understanding its relative success or failure in the broader market context.

### Liquidity and Investment Vehicle
Due to its widespread acceptance and use, the S&P 500 benefits from high liquidity. This liquidity ensures tight bid-ask spreads and allows for large transactions without significantly impacting the price, facilitating smoother entry and exit for traders and investors.

## Leveraging the S&P 500 Through Futures

### Access to Leverage
Futures markets related to the S&P 500 offer traders the ability to leverage, amplifying their investment's potential returns. While leverage increases risk, it also opens up opportunities for significant gains from relatively small market movements.

### Hedging Opportunities
Futures can serve as a hedge against portfolio losses in volatile markets. By taking positions in S&P 500 futures, investors can protect themselves against downturns in the broader market, securing their investments against unforeseen drops.

### Market Accessibility
S&P 500 futures markets operate nearly 24/7, providing flexibility and accessibility that's not always available in traditional stock markets. This round-the-clock trading allows investors to react quickly to global economic news and events, making it an invaluable tool for those looking to stay ahead in a fast-paced market.


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
