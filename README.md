# NBA Margin of Victory Prediction
Overview
Welcome to the NBA Margin of Victory Prediction project! This project aims to predict the margin of victory (MoV) for NBA games using machine learning techniques. By leveraging historical game data, the goal is to build a model that can provide insights into how well a team is expected to perform in terms of point differentials. We want to use this data to properley bet on NBA games. 

## Dataset
The data used for this project was scraped from Basketball Reference 

## Model Training
We used well over 100 features to train our model to find patterns with the Mov. We used many kinds of models and found the best results with the XGboost model. 

## Evaluation
In assessing the performance of the NBA Margin of Victory Prediction model, the Mean Absolute Error (MAE) serves as the primary evaluation metric. MAE is a robust measure that quantifies the average absolute difference between the predicted margin of victory and the actual margin of victory. A lower MAE indicates better predictive accuracy.

### Metrics Overview
Mean Absolute Error (MAE): The MAE is calculated as the average absolute difference between the predicted and actual margin of victory for each game. It provides a straightforward and interpretable measure of prediction accuracy.

## Results
On our test data we found that we hit our goal 70% of the time hitting a 36% roi when comparing our odds to what bookies put up.
