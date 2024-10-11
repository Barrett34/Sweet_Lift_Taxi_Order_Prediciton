# Sweet_Lift_Taxi_Order_Prediciton

## Introduction

Sweet Lift Taxi company has collected historical data on taxi orders at airports. To attract more drivers during peak hours, we need to predict the amount of taxi orders for the next hour. Build a model for such a prediction.

## Data Description

- taxi.csv
- num_orders - number of orders

## Conclusion
After reading and resampling the data to show the number of orders per hour, we see that the data is stationary in all months. From looking at the trend and seasonality, the orders seem to stay consistent with a substantial increase over time. August seemed to be the month where there is a large increase in orders called.

Using LinearRegression, Random Forest, and hyperparameter tuning with the DecisionTree, we found that the RandomForest model had the lowest RMSE score of 3. Overall the real number of taxi orders for a specific hour is 100, the model's predictions range from 52.61
