## Introduction: 
Welcome to the project on UPI fraud detection using machine learning! In this project, I aim to develop machine learning models to detect fraudulent transactions in UPI (Unified Payments Interface) data.

## Data Source:
The dataset used in this project is a synthetically created dataset containing 50,000 rows of UPI transaction data. It has been modified to include variability and patterns for fraud detection purposes.

## About the Dataset
The dataset contains transaction data related to UPI (Unified Payments Interface) transactions. It includes various features related to transactions and fraud indicators. It includes the data for fraudulent transactions for financial year 2023 to 2024.

## Methodology
Data Preprocessing: Cleaning the data, handling missing values, encoding categorical features, and scaling numerical features.

Exploratory Data Analysis: Understanding the distribution of features and identifying patterns related to fraud.

Feature Engineering: Creating new features or transforming existing ones to improve model performance.

Model Development: Training machine learning models for fraud detection.

Model Evaluation: Assessing model performance using metrics such as accuracy, precision, recall, and F1-score.

Conclusion: Summarizing findings and discussing potential areas for improvement.

## Project Conclusion

Throughout this project, I evaluated the performance of four distinct machine learning models for fraud detection in financial transactions: Decision Tree, Random Forest, Gradient Boosting, and XGBoost.

After a comprehensive analysis, it is evident that the XGBoost model outperforms the other models in terms of accuracy, precision, recall, F1-score, and ROC AUC score. Despite the rigorous hyperparameter tuning performed on all models, XGBoost consistently demonstrated superior predictive capabilities, making it the most suitable choice for detecting fraudulent transactions in this context.

By saving the trained XGBoost model as a pickle file, I ensure its accessibility and deployment for real-time fraud detection tasks. This model can serve as a valuable tool in financial institutions, enabling them to proactively identify and prevent fraudulent activities, thereby safeguarding both businesses and customers from potential financial losses.
