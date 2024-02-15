# Review-Predictor

This project was created using the following Kaggle Dataset for Steam reviews: https://www.kaggle.com/datasets/souyama/steam-reviews

The goal was to establish if a trained model can predict if a review written by a user had a positive rating. The input include the 'review', 'label' (Positive review) and multiple date-times.

Amazon Web Services was used to process the information before the feature engineering and data cleaning was done in databricks community edition.
AWS:

S3- Store models, raw data, feature engineering, data plots

EC2- Import the data from the kaggle API and break down the nested JSON loops.


