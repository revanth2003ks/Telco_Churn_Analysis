# Telco_Churn_Analysis

📊 Telco Customer Churn Analysis

🚀 Project Overview
This project focuses on analyzing customer data from a telecom company to understand the key factors influencing customer churn. The objective is to perform Exploratory Data Analysis (EDA) and build machine learning models to predict whether a customer is likely to leave the service.By identifying patterns in customer behavior, service usage, and billing, this project provides actionable insights to improve customer retention strategies.

🎯 Objectives
Analyze customer data to identify churn patterns
Perform data cleaning and preprocessing
Conduct detailed EDA (Exploratory Data Analysis)
Build predictive models for churn classification
Generate business insights for decision-making

📂 Dataset Description
The dataset contains information about telecom customers, including:
Customer Information: Gender, Senior Citizen, Partner, Dependents
Services: Phone Service, Internet Service, Online Security, Tech Support
Account Details: Contract Type, Tenure, Payment Method
Billing: Monthly Charges, Total Charges
Target Variable: Churn (Yes/No or 1/0)

🛠️ Technologies Used
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
Imbalanced-learn (SMOTEENN)
🔍 Exploratory Data Analysis (EDA)

Performed in-depth analysis to understand:
Distribution of customer churn
Relationship between churn and categorical variables
Impact of numerical features like tenure and monthly charges
Missing value analysis

📈 Key Insights
Customers with month-to-month contracts have higher churn rates
Higher monthly charges are associated with increased churn
Customers with low tenure are more likely to churn
Lack of online security and tech support increases churn probability

🤖 Machine Learning Models
🌳 Decision Tree Classifier
Easy to interpret
Captures non-linear relationships
🌲 Random Forest Classifier
Ensemble model for better accuracy
Reduces overfitting

⚖️ Handling Imbalanced Data
Applied SMOTEENN technique
SMOTE → Oversampling minority class
ENN → Cleaning noisy samples

📊 Model Evaluation
Models were evaluated using:
Accuracy
Confusion Matrix
Precision & Recall
Classification Report
