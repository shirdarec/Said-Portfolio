# Said-Portfolio (ML applied to trading)

# [Project I: Developing and optimizing with backtesting](https://github.com/shirdarec/Said-Portfolio/blob/main/Project_I-main/BollingerBand_optimized.ipynb)
* I picked the Bollinger Bands strategy, using the version that Rayner Teo ( famous youtuber in the trading community) used. 
* Using the yfinance library to get data from Yahoo Finance.
* Implemented the strategy with some tweakble paramteres 
* I used the plotly library to visualize the trade signals 
* Then I used backtesting library to further viusalize the results and the statistics   
* At last I made a table with all the different paramteres I tweaked to optimize the strategy 

![](https://github.com/shirdarec/Said-Portfolio/blob/main/images/project1.JPG)

# [Project II: A simple tradingbot trading in Binance](https://github.com/shirdarec/Said-Portfolio/blob/main/Project_II-main/tradinbotTest2.ipynb)

* Connected my binance account and built a clinet API to stream the BTCUSDT currency pair data.
* Made a dataframe from the live data and transferred it to a sqlite database 
* Built a simple trend-following strategy
* Used the Binance client to execute live trades 


![](https://github.com/shirdarec/Said-Portfolio/blob/main/images/project2.JPG)

# [Project III: Finding the optimal indicator for your strategy using machine learning](https://github.com/shirdarec/Said-Portfolio/blob/main/Project_III-main/TA_ML.ipynb)

* Created a tool that helps developers to find the optimal trading indicator for their strategies .
* Scraped 3 years of data for USD currency 
* Used the pandas_ta library to chose indicators and join them togehter with existing dataframe
* Used XGBClassifier to determine what indicator yields the best performance 


![](https://github.com/shirdarec/Said-Portfolio/blob/main/images/project3.JPG)
