# Introduction

This project is part of a Kaggle competition aimed at predicting customer churn using bank data. The goal is to develop effective machine learning models to identify potential churners and understand the key factors contributing to customer attrition.

# Table of Contents of the repository
 
- Data
    - df.csv (Cleaned training data)
    - test.csv (Data for model testing)
    - train.csv (Original training data)

- EDA and preprocessing of data.ipynb
    - Data quality assessment
    - Univariate analysis of numerical variables
    - Bivariate analysis of numerical variables
    - Univariate analysis of categorical variables
    - Bivariate analysis of categorical variables
    - Data preprocessing steps

- UnderSampling_Training.ipynb
    - Basic models without parameter tuning
        - Logistic Regression
        - Decision Tree
        - Random Forest
        - KNN
        - Naive Bayes
    - GridSearch for Random Forest
    - Complex base models without parameter tuning
        - Gradient Boosting
        - XGBoost
        - LightGBM
    - Complex base models with simple parameter tuning
        - GridSearch for Gradient Boosting
        - GridSearch for XGBoost
        - GridSearch for LightGBM

- UnderSampling_BestModels.ipynb
    - K-folds with ensemble models (LGBM, XGBoost, Gradient Boosting) using VotingClassifier
    - K-folds with ensemble models (LGBM, XGBoost, Gradient Boosting) using StackingClassifier

- OverSampling_Training.ipynb
    - Complex base models without parameter tuning
        - Gradient Boosting
        - XGBoost
        - LightGBM
    - Complex base models with simple parameter tuning
        - GridSearch for Gradient Boosting
        - GridSearch for XGBoost
        - GridSearch for LightGBM

- OverSampling_BestModels.ipynb
    - K-folds with ensemble models (LGBM, XGBoost, Gradient Boosting) using VotingClassifier
    - K-folds with ensemble models (LGBM, XGBoost, Gradient Boosting) using StackingClassifier

# Next Steps

The upcoming experiments will focus on dimensionality reduction and feature selection to mitigate overfitting. Additionally, numerical variables will be standardized and scaled using techniques such as Min-Max scaling to enhance model performance.
