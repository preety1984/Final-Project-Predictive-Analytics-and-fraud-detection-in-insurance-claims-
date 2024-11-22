# Final-Project-Predictive-Analytics-and-fraud-detection-in-insurance-claims-

predictive analytics and fraud detection in insurance involves several stages and focuses, as outlined in your presentation. Here's a summary:

Project Overview:
Objective: To analyze an insurance claims dataset for fraud detection and uncover key trends related to claim patterns and customer demographics.
Goal: Streamline operations, reduce fraud, and improve customer satisfaction.
Dataset:
Dependent Variable: Fraud reported (Y or N).
Independent Variables:
Categorical: Gender, education, occupation, incident type, etc.
Numerical: Age, claim amounts, incident timing, etc.
Key Data Processing Steps:
Handling Missing Data: Replace missing values (? → NaN) and fill them appropriately.
Column Removal: Excluded unnecessary or redundant columns like policy_number, incident_location, etc.
Outlier Detection: Used techniques like Isolation Forest to handle outliers.
Correlation Analysis: Identified and addressed multicollinearity using Variance Inflation Factor (VIF).
Machine Learning Models:
Implemented multiple models:
Random Forest Classifier
Logistic Regression
K-Nearest Neighbors
Support Vector Machine
Gradient Boosting
Extra Trees
XGBoost
Best Performer: Extra Trees
Accuracy: 90.73%
Benefits: High accuracy, robustness, ease of interpretation, and generalization.
Performance Metrics:
High accuracy (89.2%) for fraud detection.
Recall (92.5%) highlights strong ability to minimize false negatives.
Balanced precision (87.6%) and F1-score (90%).
tableau link: Fraud detection using tableau | Tableau Public
![image](https://github.com/user-attachments/assets/f1e39d30-eb8a-4903-8e0a-6d9b4bf4db31)

