# Mod_4_Bitcoin_Project

## Project Presentation:
https://www.canva.com/design/DAD7fgzkfiY/XNuka_HszjbjI1prozvYAA/edit?category=tACFasDnyEQ

### Project Details:
Data Source: Yahoo Finance

#### Goals  
- Identifying the Lows and Highs of closing prices.
- See if there are other opportunities that can be seized.

#### Problems:
- Prices change over time. So last years price may be different from today's price. 
- When buying, we want to know if that is the lowest point or just a regular low. How can we find the best possible low to enter the market at that specific price.
- We don't know when would be a good opportunity to make trades.

#### Solutions:
- Using indicators to help identify the best possible prices to buy or sell.
- MACD(Moving Average Convergence Divergence), RSI(Relative Strength Index), STD(Standard Deviation)
- Finding the local minima and maxima would be the best option. After that we can train our model on those labels and see how well if predicts on the dataset as a whole. 

#### Recommendations for further developments:
- Add more indicators/feature engineering
- Figure out how to solve for the drastic price drops or increases, so our model can learn better.
     
  
## Project Findings:
- Outside of the True High/Lows, I was able to find other price points that could be possible high/low.
- The window period for MACD influenced the prediction of the model. So adjusting the window can help improve or diminish the results.
  
### Methods Used
* Statistics
* Data Cleaning
* Data Organizing/Exploring
* Feature Engineering
* Machine Learning
* Data Visualization
* Predictive Modeling


### Metrics Used:
- roc_auc_score : I wanted a metric that shows to well the model distingushes between two classes. 
- Standard Deviation

    
### Technologies
* Python
* Pandas, Jupyter
* Matplotlib
* Numpy
* Scikit learn


## Needs of this project
- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- high/low indications
- help solidify our trading choices
- give us an idea or estimate of where the high/lows are and what they look like


#### Project Members:

|Name     |  Github   | 
|---------|-----------------|
|[Anh Phan](https://github.com/anhbiphan)


