# Bitcoin_Project

**Data Source**: Yahoo Finance  

### Project Goals:
- Identifying the Lows and Highs of closing prices.
- Train and validate model to predict closing prices.
- Discover if there are other closing price opportunities.

#### Problems:
- Identify closing price labels. Possibly use a 0 or 1 to indicate if price is best (low/high) in a window time frame?
- Feature engineer graphing tools to provide extra information.
- What is the best window time frame to use?

#### Solutions:
- MACD(Moving Average Convergence Divergence), RSI(Relative Strength Index)
- Finding the local minima and maxima would be the best option in creating labels. 
- Feature engineer VWAP (Volume Weighted Average Price) uses both price and volume to measure average price traded that day.

#### High Closing Price Prediction + Graph + Score
![alt text](https://github.com/anhbiphan/Project_Bitcoin/blob/Anh/images/high_preds.png?raw=true)

#### Low Closing Price Prediction + Graph + Score
![alt text](https://github.com/anhbiphan/Project_Bitcoin/blob/Anh/images/low_preds.png?raw=true)



#### Recommendations for further developments:
- Add more indicators/feature engineering
- Figure out how to solve for the drastic price drops or increases, so our model can learn better.
     
  
## Project Findings:
- Outside of the True High/Lows, I was able to find other price points that could be possible high/low.
- The window period for MACD influenced the prediction of the model. So adjusting the window can help improve or diminish the results.
  

#### Project Members:

|Name     |  Github   | 
|---------|-----------------|
|[Anh Phan](https://github.com/anhbiphan)


