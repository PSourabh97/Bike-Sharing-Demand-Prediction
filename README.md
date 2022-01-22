# Bike-Sharing-Demand-Prediction
## Problem Description-
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
## Objective of our Project-
* Observasion of factors which effect the Bike demand in our dataset.
* Selection the best model for prediction.
* Count of Bike demand w.r.t 'Hour', 'Seasons', 'Month'.
## Steps involved to complete the project-
At first I have done Exploratory Data Analysis after then I have done Null value treatment, Feature selection, Standardization and finally I have fit the model in different machine learning Algorithm. The models I have used here are –

Linear Regression,  Lasso Regression, Decision Tree, Random Forest, XGBoost Algorithm .

After applying the models I have done Hyper tuning using GridSearchCV.

After Hyper Tuning I have checked the performance by using the Performance Matrices.

The matrices I have used here are-
R2 Score, Adjusted R2 score, Mean Square Error, Mean Absolute Error, Root Mean Absolute Error.
## Conclusion-
Here in this project XGBoost model is performing so well and we got some conclusion-

Working or Non- working Day We see 2 rental patterns across the day in bike
rentals count - first. for a Working Day where the rental count high at peak
office hours (8am and 5pm) and the second for a Non-working day where
rental count is more or less uniform across the day with a peak at around
noon.

Temperature: People generally prefer to bike at moderate to high
temperatures. We see highest rental counts between 32 to 35 degrees
Celsius.

Season: Demand of rental bikes is high between February to October.

Weather: As one would expect, we see highest number of bike rentals on a
clear day and the lowest on a snowy or rainy day.

Humidity: With increasing humidity, we see decrease in the number of bike
rental count.


