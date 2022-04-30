# Rainfall-Prediction-Using-Machine-Learning
Rainfall Prediction is one of the difficult and uncertain tasks that have a significant impact on human society. Timely and accurate forecasting can proactively help reduce human and financial loss. This study presents a set of experiments that involve the use of common machine learning techniques to create models that can predict whether it will rain tomorrow or not based on the weather data for that day in major cities in our country.
# Tech Stack
Front-End: HTML, CSS, Bootstrap
Back-End: Flask
IDE: Jupyter notebook, Pycharm
Data Collection:
Rainfall Prediction in Australia dataset from Kaggle

# Data Preprocessing:
Missing Values Handled by Random Sample imputation to maintain the variance
Categorical Values like location, wind direction are handled by using Target guided encoding
Outliers are handled using IQR and boxplot
Feature Selection and was done but didnt perform well it can be seen in testing_notebook/Prediction.ipynb
Feature Scaling didnt give a lot of difference it also can be seen in testing_notebook/RainPrediction1.ipynb
Imbalanced Dataset was handled using SMOTE
# Model Creation:
Different types of models were tried like catboost, random forest, logistic regression, xgboost, support vector machines, knn, naive bayes.
Out of these catboost, random forest and support vector machines were top 3
The conclusion were made using classification metrics. roc curve and auc score
Model Deployment
