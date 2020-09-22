# Predicting and Analyzing Telecom Churn Rates

This project consists of an analysis of [Telecom Customer Churn Rates] (https://www.kaggle.com/zagarsuren/telecom-churn-dataset-ibm-watson-analytics) with data collected by IBM Watson Analytics. 

I created a classification model used to predict if a telecommunications customer would churn from their services. This project was utilized as one of my capstone projects I submitted for Thinkful's Data Science Bootcamp curriculum. The time frame given to complete this project was roughly around one week; however, I was able to finish the project within a couple days. As a result of having extra time to work on the project, I was able to perform multiple different feature engineering techniques on the dataset (SelectKBest with K = 10, K = 15, and also Principle Component Analysis). 

### Results of the Classification Models

A total of 4 different classification models were used to predict the customer churn outcome: 

1) KNearestNeighbors Classifier

2) Support Vector Classifier

3) Random Forest Classifier

4) Gradient Boosted Classifier. 

Each model was initially executed without SelectKBest or PCA. Once results were obtained, SelectKBest with K = 15 was applied to each model, then SelectKBest with K = 10, and then finally PCA.
