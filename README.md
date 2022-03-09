# Project Name
> Build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not by using the available independent variables
 
## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The company is looking at prospective properties to buy to enter the market. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

- The dataset "train.csv" that is being used contains 81 columns and 1460 records

## Conclusions
- The target variale is the sale price of houses. The data given in the dataset was cleaned and checked for effect on the sale price. Business metrics were derived using available features.
- Certain objective variables with high skewness were removed.
- RFE was used to get the 50 most significant variables.
- Linear, Ridge and Lasso regressions were implemented on the dataset.Lasso worked better than Ridge on the dataset
- Features like BsmtFullBath, OverallCond, MasVnrArea, HeatingQC, OverallQual has significant affect on the SalePrice


## Technologies Used
- pandas - version 1.2.4
- numpy - version 1.20.1
- seaborn - version 0.11.1
- matplotlib - version 3.3.4
- statsmodels.api - version 0.12.2
- sklearn - version 0.24.1

## Acknowledgements
- This project was inspired by Upgrad
- This project was based on [this tutorial](https://learn.upgrad.com/course/1992/segment/12361/109310/330592/1718183).

## Contact
Created by [@nehu7] - feel free to contact me!
