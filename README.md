# ecs171-group2-rain-australia

Problem: The aim of this project is to predict whether it will rain tomorrow in Australia, and to compare how that prediction problem changes across seasons. Rain forecasting is widely used daily (i.e., to determine if someone should bring an umbrella or water the plants on a given day). However, it is a challenging problem to answer since rain depends on various interacting weather variables. It is important to determine which of those variables matter most and whether the important features stay consistent across seasons or shift. To make the problem more substantive, this project will train and evaluate models on three slices of the data: summer only, winter only, and both combined, then compare how well the same model performs on each.

Dataset: The “Rain in Australia” dataset from Kaggle 
https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package

Prediction Goal: Given the weather measurements for a given summer day, predict whether or not it will rain the next day (Yes/No). 

Criteria: A reasonable target is beating the majority class baseline (always predicting "No rain") by a meaningful margin on F1 score.
