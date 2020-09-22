# Predicting and Analyzing Telecom Churn Rates

This project consists of an analysis of [Telecom Customer Churn Rates] (https://www.kaggle.com/zagarsuren/telecom-churn-dataset-ibm-watson-analytics) with data collected by IBM Watson Analytics. 

I created a classification model used to predict if a telecommunications customer would churn from their services. This project was utilized as one of my capstone projects I submitted for Thinkful's Data Science Bootcamp curriculum. The time frame given to complete this project was roughly around one week; however, I was able to finish the project within a couple days. As a result of having extra time to work on the project, I was able to perform multiple different feature engineering techniques on the dataset (SelectKBest with K = 10, K = 15, and also Principle Component Analysis). 

### Classification Models

A total of 4 different classification models were used to predict the customer churn outcome: 

1) KNearestNeighbors Classifier

2) Support Vector Classifier

3) Random Forest Classifier

4) Gradient Boosted Classifier. 

Each model was initially executed without SelectKBest or PCA. Once results were obtained, SelectKBest with K = 15 was applied to each model, then SelectKBest with K = 10, and then finally PCA.

### The Best Classification Model

Although the models all had their own pros and cons, I believe the KNearestNeighbor with SelectKBest of K = 10 model had the best performance. The KNN Classification model had the most well rounded scores for both precision and recall. Other models were able to successfully predict true positives or true negatives, however they often ended up favoring one over the other. The KNN model, on the other hand, happened to have a high success rate for determining both true positives **and** true negatives. 

### Improvements and Final Thoughts

One area that I know can be focused on for improvements is looking more into bias within the data. Adding feature importances to each of my models would help to visualize whether one feature outweighed another. I could also make some slight changes to my classification report and confusion matrices to help make them more understandable. Overall, this was a very enjoyable first supervised learning project and I am looking forward to not only improving this project, but also working on many more. 
