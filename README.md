# COMP 562 FALL 2021 Final Project
This is the final project for COMP 562 (Introduction to Machine Learning) in Fall 2021.

## Team Member
Zhuofan Ying, Hanqi Hua

## Project Detail
In this project, we attemped to use machine learning techniques to predict the hotel reservation cancellation. In particular, we analyzed the [dataset](https://www.sciencedirect.com/science/article/pii/S2352340918315191) published by Elsevier. This dataset consists of two hotels’ demand data. One is a resort hotel (H1) and the other is a city hotel (H2). The data for both hotels share the same structure, with 31 variables describing the 40,060 observations of the first hotel and 79,330 observations of the other. 

We did EDA to select the most significant features, such as lead_time and total_of_special_requests, to be our predictors. Next, Logistic Regression, Gaussian Naive Bayes, XGBoost, and Neural Network are trained to predict if a single would be canceled or not. The model with best performance will be chosen as our final model. 

## Acknowledgement
Our main code for data cleaning is adapted from [Kaggle](https://www.kaggle.com/sanjana08/hotel-booking-cancellation-prediction). 
