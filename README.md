# Project Name
> * Assignment : Surprie Housing Price Modeling 
> * Team Member :  Lokesh Gaddam
> * Date : 24Jan2024
 
 
## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
 
 
## General Information
> ### Business Understanding :
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
> The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
> The company wants to know:
> Which variables are significant in predicting the price of a house, and
> How well those variables describe the price of a house. 
> Also, determine the optimal value of lambda for ridge and lasso regression.
> ### Objective:
> Objective is to model the price of houses with the available indepmendent variables. 
> This model will then be used by the management to understand how exactly the prices vary with the variables. 
> They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. 
> Further, the model will be a good way for management to understand the pricing dynamics of a new market.
 
 
## Conclusions
> ### EDA Summary 
>Conclusion Summary:
> * Linear regression => Train is 92% vs Test is 87.5% where the difference is more
> * Ridge regression => Train is 90% vs Test is 87.4%
> * Lasso regression => Train is 90% vs Test is 87.2 %
> * so both Ridge and Lasso have a pretty good score

>Top 5 most significant variables in Ridge are as follow:
> * ('GarageFinish_RFn', 0.092)
> * ('GarageFinish_Unf', 0.094)
> * ('SaleCondition_Normal', 0.099)
> * ('SaleCondition_Others', 0.105)
> * ('SaleCondition_Partial', 0.143)

>Top 5 most significant variables in Lasso as follows:
> * ('GarageFinish_RFn', 0.091)
> * ('GarageFinish_Unf', 0.098)
> * ('SaleCondition_Normal', 0.109)
> * ('SaleCondition_Others', 0.129),
> * ('SaleCondition_Partial', 0.218)
> * Hyper parameters for Ridge and Lasso are as follows :
> * Optimal value for Ridge : 10
> * Optimal value for Lasso : 0.001

> * In this case both Ridge and Lasso regression selection seems to be good , however since Lasso has the feature selection ability and hence Lasso is choosen over Ridge in thsi case
 
 
## Technologies Used
> - Jupyter note book v2.5.0
> - python3 & necesary libraries for statistics, visualization and modeling 
 
 

 