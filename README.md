# Podcast-Listening-Time-Prediction
Main goal of this project is to build regression machine learning model for predicting podcast listening time based on such features as episode length, number of ads, episode opinions and miscellaneous categorical features like podcast channels, topic, genre and publication time.

## Project content
This project additionaly involves:

+ Exploratory Data Analysis
+ Data Preprocessing
+ Testing Data Imputing ML methods
+ Feature engineering
+ Testing different regression models
+ Analysing model results and importance of features
+ Visualisations in total of 35 informative plots.

Most of individual decisions are provided with explanations and comments.

## Dataset
This project was based on AI created training dataset from newest (up to april of 2025) kaggle competition https://www.kaggle.com/competitions/playground-series-s5e4

## Libraries
+ numpy
+ matplotlib
+ pandas
+ seaborn
+ scikit-learn
+ xgboost
+ lightgbm
+ dotenv
+ sqlalchemy
+ verstack
+ category_encoders
+ joblib

## Key Findings
+ The most major factor in predicting listening time was unsuprusingly episode length, with correlation of 0.92.
+ Since that, linear regression was 15 times faster and had only 10% worse result on cleaned data
+ Podcast listening time has clear dependence on number of ads and especially amount of ads per minutes.
+ Number of ads also shows influence on episode sentiment
+ However, despite 1 plot showing clear median dependence for episode sentiment on listening time, all of the models almost null it.
+ Other categorical features didn't showed off in model results as well
