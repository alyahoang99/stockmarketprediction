# stockmarketprediction
## Type of stock market price predictions 
The stock market price prediction can be broadly classified into three categories depending on the usage, the dataset used and the technology involved 
- Fundamental Analysis: fundamental analysis is based on the principle that a company's performance directly affects its stock prices. The data, like the company's reputation and vision for the future, play a key role.
- Technical analysis: identify trading opportunities based on patterns of historical trading price and trading volume.
- Technological methods: the revolution in the capabilities of AI, paired with the advancements in the computer hardware industry, led to support the power-hungry AI efficiently. It has led to a boom in replacing manual analysis with a highly accurate and quicker analysis done by ML models explicitly trained for the task. 
## Problem statement 
Predict the closing price of a particular stock using the historically available prices of the said stock, eg: given the previous 15 days' closing price, try and predict the 16th-day closing price. 
## Data analysis 
- Open -> the stock's opening price for a particular day
- Close -> the stock's closing price for a specific day
- High -> indicates the highest price of the stock for a day
- Low -> lowest price for a day
- Volume -> number of Amazon's shares traded in a day
- Adj (adjacent) close -> the closing price but is a more accurate measure of the stock's value as it considers other factors such as dividends.
The total length of the dataset is 250, even though there are 365 days in a year. This discrepancy happens as the stock market only open 5 days a week.

### Feature Selection 
Infer the patterns 
- even though high and low prices differ, they don't differ by much
- no considerable variation in opening and closing prices for a day
- the opening price of today is very similar to the closing price of the previous day
- the closing price is continuous except for a few days.

### Data pre-processing 

### Training ANN model 
