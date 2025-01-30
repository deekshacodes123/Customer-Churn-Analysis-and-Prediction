This project focuses on Exploratory Data Analysis (EDA) and predictive modeling to analyze customer churn behavior. Customer churn, or attrition, occurs when customers stop using a service, impacting revenue and profitability. Understanding the key drivers behind churn helps businesses improve customer retention strategies.

##Dataset
The dataset used in this project is sourced from Kaggle.

##Key Features:
Demographic Data: Geography, Gender, Age
Account Information: Credit Score, Tenure, Balance, NumOfProducts, Estimated Salary
Behavioral Indicators: IsActiveMember, HasCrCard
Target Variable: Exited (indicating whether a customer churned or not)
##Technologies Used

Python (for data analysis and modeling)
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

##Key Components
Exploratory Data Analysis (EDA)
Data cleaning, handling missing values, and feature engineering
Identifying trends and correlations related to customer churn
Data Preprocessing & Handling Class Imbalance
Implemented SMOTE (Synthetic Minority Over-sampling Technique) to address class imbalance
Feature scaling and encoding categorical variables
Machine Learning Models for Churn Prediction
Logistic Regression, Random Forest, K-Nearest Neighbors, Support Vector Machine, XGBoost, and Gradient Boosting
Hyperparameter tuning for optimal performance
Performance Comparison
Model	Accuracy	    Recall Score	F1 Score ROC AUC Score
Gradient Boosting	    81.7%	70.0%	59.8%	85.9%
XGBoost          	    83.3%	60.9%	58.7%	84.1%
Random Forest	        86.2%	41.4%	53.9%	85.2%
Support Vector Machine  78.5%	66.3%	54.6%	82.2%
K-Nearest Neighbors	    75.2%	66.8%	51.2%	77.6%
Logistic Regression	    70.3%	68.3%	47.3%	76.4%
##Insights:

Gradient Boosting outperformed other models, achieving the best balance of precision and recall.
XGBoost also demonstrated strong predictive performance.
Random Forest had high accuracy but lower recall, indicating potential bias toward the majority class.
Conclusion
This project successfully implemented EDA, feature engineering, and machine learning models to predict customer churn. The findings highlight the importance of data-driven retention strategies and the effectiveness of boosting algorithms for classification tasks.