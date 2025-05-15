# Primetrade.ai---Assignment-Intershala


## Hi, ##

## Please do the below task as a first step of the hiring process. Candidates who get selected will be shortlisted for the interview ##


### Assignment Overview

You will have to work with two primary datasets:
1. Bitcoin Market Sentiment Dataset
o Columns: Date, Classification (Fear/Greed
2. Historical Trader Data from Hyperliquid
o Columns include: account, symbol, execution price, size, side, time, 
start position, event, closedPnL, leverage, etc.
Your objective is to explore the relationship between trader performance and market 
sentiment, uncover hidden patterns, and deliver insights that can drive smarter trading 
strategies.

## 1. Data Preprocessing 

-Parse and clean both datasets.

-Convert dates to a standard format and align the sentiment data with the trader data. 

-Handle missing values, if any. 

### 2. Feature Engineering 

-Add a "Market Sentiment" column to each trade in the historical data, based on the date. 

-Derive new features like: 

1.Profitability (closedPnL sign) 

2.Trade duration (if possible) 

3.Aggressiveness (using leverage, position size, etc.)

4.Sentiment at the time of trade (from the index) 

### 3. Exploratory Data Analysis (EDA) 

1.Distribution of trades under "Fear" vs "Greed". 

2.Average closedPnL under different sentiments. 

3.Leverage and position sizes across sentiment types. 

4.Identify traders who perform better during Fear vs. Greed.

### 4. Pattern Discovery 

1.Correlation matrix between sentiment and key metrics. 

2.Cluster traders based on behavior and profitability. 

3.Use decision trees or simple models to understand rules of performance under different sentiments.

### 5. Insights & Recommendations 

1.Summarize which sentiment tends to yield higher profits. 

2.Identify which trader profiles thrive under specific sentiment. 

3.Suggest strategies like lowering risk during "Fear", or maximizing opportunities during "Greed".

### Your objective is to explore the relationship between trader performance and marketsentiment, uncover hidden patterns, and deliver insights that can drive smarter trading strategies.

### Implementation of Trading Strategies
### Important Notes:

1.Trend Calculation: For the trend-following strategy, you'll need to implement your own logic to calculate the Trend column using technical indicators.

2..Backtesting: Remember to thoroughly backtest these strategies with historical data before using them in live trading.

3.Customization: Adapt the code and logic to your specific trading preferences and risk tolerance.

4.Risk Management: Always incorporate appropriate risk management measures, such as stop-loss orders and position sizing limits.




## Link to dataset

Historical Data 

https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing

Fear Greed Index link:

https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing



First come first serve, so get the task done asap
