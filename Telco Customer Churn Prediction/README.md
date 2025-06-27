# Telco Customer Churn Prediction 

**Link to Kaggle Notebook**: [Kaggle - Telco Customer Churn Prediction](https://www.kaggle.com/code/bengj10/teleco-customer-churn-prediction)

## Overview

In today's competitive telecom market, customer churn is a major concern for service providers. With annual churn rates ranging from **15% to 25%**, retaining existing customers is critical to maintaining profitability and sustaining growth.

This project focuses on building a **machine learning model** to predict customer churn using real-world telco data. By analyzing customer behavior and interaction patterns, telecom companies can proactively identify at-risk customers and implement targeted retention strategies.

---

## What is Customer Churn?

In a business context, **churn** refers to the **loss of an existing, potentially profitable customer**. The definition can vary by industry — in healthcare, churn may mean deceased patients; in finance, it can mean account inactivity.

### Why is Churn Important?
- **Cost of Acquisition > Cost of Retention**: It's significantly more expensive to acquire new customers than to retain existing ones.
- **Revenue Impact**: Churn affects both current revenue and lifetime customer value.
- **Brand Trust**: High churn rates often signal dissatisfaction and erode brand loyalty.

---

## Project Objectives

- Predict which customers are at high risk of churn
- Help telecom companies implement **data-driven retention strategies**
- Improve **customer satisfaction**, **reduce churn**, and **maximize profitability**

---

## Workflow

1. **Data Collection**  
   Obtained telco customer data containing demographics, services subscribed, and account information.

2. **Data Manipulation**  
   Cleaned and structured the dataset for analysis and modeling.

3. **Exploratory Data Analysis (EDA)**  
   Visualized key trends, correlations, and churn-driving factors.

4. **Data Preprocessing**  
   - Categorical encoding
   - Missing value handling
   - Feature scaling

5. **Data Resampling**  
   Addressed class imbalance using techniques such as SMOTE to improve model generalization.

6. **Model Training**  
   Trained multiple models including:
   - Logistic Regression
   - Random Forest
   - Gradient Boosting
   - XGBoost

7. **Model Evaluation**  
   Used metrics such as **accuracy**, **recall**, **precision**, **F1-score**, and **confusion matrix**.

---

## Results & Evaluation

From the **Random Forest** model:

- **True Negatives (1322)**: Customers correctly predicted to stay  
- **False Positives (230)**: Customers incorrectly predicted to churn  
- **False Negatives (238)**: Churned customers missed by the model  
- **True Positives (323)**: Customers correctly identified as likely to churn  

This performance demonstrates the model’s capability in identifying churn with high reliability, particularly in detecting high-risk customers — crucial for proactive interventions.

---

## Key Learnings

By integrating this predictive model into the customer lifecycle, businesses can:

- **Detect early signs of churn**
- **Offer personalized support or incentives**
- **Reduce churn rates**
- **Boost long-term revenue and loyalty**

---

## Dataset

This project uses the [Telco Customer Churn dataset](https://www.kaggle.com/blastchar/telco-customer-churn) from Kaggle. The dataset contains 7,043 customer records with 21 features including:

- Demographics: Gender, SeniorCitizen, Partner, etc.
- Services: InternetService, OnlineBackup, DeviceProtection, etc.
- Account Info: Contract, Tenure, MonthlyCharges, etc.
- Churn: Binary target variable (Yes/No)

---

## Contributions

Feel free to fork this repository, raise issues, or suggest improvements. Collaboration is welcome!

---
