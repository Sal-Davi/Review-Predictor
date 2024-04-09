# Review-Predictor

Steam is a video game service that was developed by Valve Corporation. User's are able to buy games on the Steam platform that have been publkished by either valve or third-parties. On this platform users are able to play games, engange in community posts, add friends, customize profiles and leave game reviews. The goal was to establish if a trained model can predict if a review written by a user had a positive rating. 

This project was created using the following Kaggle Dataset for Steam reviews: https://www.kaggle.com/datasets/souyama/steam-reviews
AWS & databricks were utilized for this project. The dataset was needed to be parsed(JSON) in AWS EC2 and was then stored in a S3 bucket. The S3 bucket was then referenced in the databricks notebooks to then load, clean, preprocess, train, evalute metric performance and visualziations to support our conclusion.

The input include the 'review', 'label' (Positive review) and multiple date-times.


AWS:

S3- Store models, raw data, feature engineering, data plots

EC2- Import the data from the kaggle API and break down the nested JSON loops.


