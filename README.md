# Lending-Club
Lending Club Classification using Machine Learning Techniques
Lending Club Loan Default Prediction
This project applies machine learning techniques to classify borrowers in the Lending Club dataset based on their likelihood of defaulting on a loan. The study includes extensive data preprocessing, exploratory data analysis (EDA), and the implementation of various classification models.

Project Overview
Lending Club is a peer-to-peer lending platform where investors fund borrower loans. This project aims to build a predictive model to help investors identify high-risk borrowers, thereby reducing financial losses.

Contents
Data Cleaning: Handling missing values, feature selection, and transformation
EDA (Exploratory Data Analysis): Univariate, bivariate, and multivariate analysis
Feature Engineering: Encoding categorical variables, handling outliers, and standardizing numerical features
Model Training and Evaluation:
Decision Tree
Logistic Regression
Naïve Bayes
Support Vector Machine (SVM)
XGBoost
K-Nearest Neighbors (KNN)
AdaBoost
Random Forest (best-performing model)
Hyperparameter Tuning: Using Grid Search to optimize model performance
SMOTE Implementation: Addressing class imbalance to improve model generalization
Cross-Validation: Ensuring model robustness and preventing overfitting
Key Findings
Borrowers with high interest rates are more likely to default
Borrowers with higher annual income are less likely to default
Borrowers with high revolving balance amounts are more likely to default
Borrowers with a high debt-to-income ratio are more likely to default
Conclusion
After comparing multiple models, the tuned Random Forest model with SMOTE yielded the best results for predicting loan defaults. This model provides a reliable framework for investors to assess borrower risk before funding loans.
