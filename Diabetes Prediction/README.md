# Diabetes Prediction

## Overview

Diabetes is one of the most prevalent chronic diseases worldwide, posing serious health risks if not diagnosed early. Predicting the likelihood of diabetes can help in taking preventive measures and ensuring timely medical intervention.  

This project develops a **machine learning model** using a **Support Vector Machine (SVM)** classifier to predict whether a person is likely to have diabetes, based on diagnostic health data.

---

## Project Objectives

- Use health-related attributes to predict diabetes occurrence  
- Apply **Support Vector Machine (SVM)** for classification  
- Evaluate model performance with appropriate metrics  
- Demonstrate an end-to-end ML workflow on a healthcare dataset  

---

## Workflow

1. **Data Collection**  
   Used the **Pima Indians Diabetes Dataset**, a widely used benchmark dataset for diabetes prediction.  

2. **Data Exploration & Cleaning**  
   - Analyzed correlations among features such as glucose level, BMI, age, and insulin  
   - Handled missing or zero values in medically relevant features  
   - Normalized feature scales for SVM compatibility  

3. **Feature Engineering**  
   - Standardized data to ensure fair comparison across features  
   - Identified the most significant predictors of diabetes  

4. **Model Training**  
   - Implemented **Support Vector Machine (SVM)** with different kernels (linear, RBF, polynomial)  
   - Split dataset into training and testing sets  

5. **Evaluation**  
   - Metrics: **Accuracy, Precision, Recall, F1-score, Confusion Matrix, ROC-AUC**  
   - Compared kernel performance and selected the best configuration  

---

## Results

- The **SVM with RBF kernel** delivered the highest accuracy on the test set.  
- Key predictors included **glucose levels, BMI, age, and blood pressure**.  
- Model achieved strong recall, highlighting its ability to correctly identify positive diabetes cases.  

---

## Key Learnings

- SVMs are highly effective for binary classification tasks with proper scaling

- Data preprocessing, particularly normalization, is essential for SVM performance

- Healthcare prediction tasks require balancing accuracy with recall to minimize false negatives
