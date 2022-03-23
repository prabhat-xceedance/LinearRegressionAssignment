# Bike Sharing Demand Linear Regression Assignment
> This assignment is a programming assignment wherein we have to build a multiple linear regression model for the prediction of demand for shared bikes.

## General Information
- This is for an assignment for upGrad where we are required to build a multiple linear regression model for the prediction of the demand of shared bikes.
- We are required to model the demand for shared bikes with the available independent variables. 
- It will be used by the management to understand how exactly the demands vary with different features. 
- They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. 
- Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Conclusions
- Number of predictors n = 11
- The independent variables that were used in final model are- 'yr', 'holiday', 'temp', 'hum', 'windspeed', 'summer', 'winter', 'Monday', 'Light Snow/Rain','Tuesday', 'Mist and Cloudy'
- Among this 3 most important features were - temp, Light Snow/Rain, year This was decided by inspecting absolute value of their coefficient. 
- The model is also validated against serveral assumptions of Linear Regression - linearity, normally distributed error, contant variance of error.
- The model is evaluated by R2_score and RMSE. R2_score of 0.8368 means 83.68% of variance in the data is explained by the model. 
- RMSE or Root Mean Squarred Error is calculated in the same unit as the target variable. RMSE of 781 means, the prediction made by this model can be over or underestimated by 781 units at maximum.


## Contact
Created by https://github.com/prabhat-xceedance - feel free to contact me!
