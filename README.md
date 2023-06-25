# Response-Modeling-and-Campaign-Strategizing-for-Supermarket

## Problem Statement:
A supermarket chain runs marketing campaigns with multiple offers on different products and services to boost sales. 

## Objectives:
Leveraging the spend behavior and past campaign responses to build a response model that can be used to devise a campaign strategy for achieving the objectives.

To improve responses.The supermarket is actually looking to get more responses from their marketing campaigns.

To maximise the profit, maximise the return on investment made towards these marketing campaigns.

# Algorithms Used :
In this project we have used Logistic Regression, Decision Tree, Random Forest, Gradient Boosting Machine 

# Final Model Algorithm
Among the models that we tried building the Gradient Boosting Machine   performed the best in terms of F1_Score

Therefore we have kept Gradient Boosting Machine  as the final model algorithm

# Grid Search CV parameters
Maximum Depth of Tree - 6

Minimum Sample Size for Nodes to be Split - 75 Observations

# Model Performance Measures
Accuracy from GBM Model : 0.885

Precision from GBM Model : 0.671

Recall from GBM Model : 0.4343

f1_score from GBM Model : 0.527
Area under ROC Curve from Random Forest Model : 0.698


## Strategy build for creating the campaign :
1) Audience should be the top 20% of the people as per the ranked data. This would lead to 80% reduction in Marketing cost and higher response rate.

2) 1st Priority : People with Low Engagement and High Spend

   2nd Priority : People with High Engagement and High Spend

   3rd Priority : People with High Engagement and Low Spend

   4th Proirity : People with Low Engagement and Low Spend

3) The best offers should be provided on the following products: Wines/Fish/Meat/Gold
