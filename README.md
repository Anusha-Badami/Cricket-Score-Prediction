CRICKET SCORE PREDICTION

Problem Statement:-
Cricket Score Prediction using Machine Learning

Objective:-
The objective of this project is to develop a machine learning model that can accurately predict cricket scores based on historical match data

Dataset Columns:-
mid: Each match is assigned a unique identification number.
date: Indicates the date when the match took place.
venue: Refers to the stadium where the match is being conducted.
bat_team: Denotes the name of the team currently batting.
bowl_team: Represents the name of the team currently bowling.
batsman: Specifies the name of the batsman facing the ball at that moment.
bowler: Specifies the name of the bowler delivering the ball at that moment.
runs: Represents the total runs scored by the batting team up to that instance.
wickets: Indicates the total number of wickets fallen for the batting team up to that instance.
overs: Denotes the total number of overs bowled up to that instance.
runs_last_5: Represents the total runs scored by the batting team in the last 5 overs.
wickets_last_5: Indicates the total number of wickets fallen by the batting team in the last 5 overs.
striker: Refers to the batsman with the higher number of runs between the striker and non-striker.
non-striker: Refers to the batsman with the lower number of runs between the striker and non-striker.
total: Denotes the total runs scored by the batting team after completing their first innings.

Algorithms Used:-
Linear Regression 
Random Forest Regression 

Features and Label Used:-
Features: [runs,wickets,overs,striker,non-striker]
Label: [total]

Linear Regression:-
R Square Value: 52
Custom Accuracy: 43

Random Forest Regression:-
R Square Value: 79
Custom Accuracy: 77

Interpretation:-
R Square Value:
R Square (R^2) is a statistical measure that represents the proportion of the variance in the dependent variable that is predictable from the independent variables. It ranges from 0 to 1, where 1 indicates a perfect fit.
In this context, the Random Forest Regression model has a significantly higher R Square value (79) compared to Linear Regression (52). This indicates that the Random Forest model explains a larger proportion of the variance in the data, suggesting a better fit.

Custom Accuracy:
Custom Accuracy is defined based on the difference between the predicted score and the actual score. If this difference falls below a particular threshold (20 in this case), it is counted as a correct prediction.
The Random Forest Regression model has a higher Custom Accuracy (77%) compared to Linear Regression (43%). This means that the Random Forest model is better at making accurate predictions within the specified threshold.

Conclusion:-
Based on the provided metrics, the Random Forest Regression model outperforms the Linear Regression model in terms of both R Square Value and Custom Accuracy. Here's why:

R Square Value: A higher R Square value indicates that the Random Forest model explains a larger proportion of the variance in the data, suggesting a better fit. This means that the Random Forest model captures the relationship between the features and the target variable more effectively.

Custom Accuracy: The Random Forest model achieves a significantly higher Custom Accuracy, indicating that it makes more accurate predictions within the specified threshold. This suggests that the Random Forest model better captures the nuances of the data and provides more reliable predictions.

Therefore, based on these metrics, the Random Forest Regression model is considered better suited for predicting ODI matches, as it offers higher predictive accuracy and captures more variance in the data compared to Linear Regression.
