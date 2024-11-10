# Thyroid Cancer Recurrence
Classification Model to Predict Thyroid Cancer Recurrence

Steps:
- Exploratory Data Analysis
- Feature Engineering with statistical testing to determine most relevant features
- Implementation of a machine learning model using XGBoost for classification, with Stratified K-Fold cross validation since the dataset is imbalanced, and using two-stage cross validation with regularization to avoid overfitting
- Model evaluation with Recall since the consequences of false negatives being more severe than those of false positives in this problem

Dataset from Kaggle: https://www.kaggle.com/datasets/jainaru/thyroid-disease-data
