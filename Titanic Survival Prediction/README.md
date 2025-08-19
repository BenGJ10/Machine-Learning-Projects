# Titanic Survival Prediction

**Link to Kaggle Notebook**: [Kaggle - Titanic Survival Prediction](https://www.kaggle.com/c/titanic)

## Overview

The sinking of the **RMS Titanic** in 1912 remains one of history’s most infamous maritime disasters. Out of more than 2,200 passengers and crew, only about 710 survived. Survival chances were influenced by factors such as **age, gender, class, and travel companions**.

This project aims to build a **machine learning model** that predicts the likelihood of a passenger surviving the Titanic tragedy, based on real passenger data provided by Kaggle. The project is a classic benchmark for practicing classification tasks.

---

## What is the Titanic Dataset?

The Titanic dataset is one of the most widely used datasets in data science and machine learning education. It contains detailed passenger records including demographics, ticket information, and survival status.

### Why is This Problem Important?
- **Foundational Classification Task**: Serves as a starting point for learning supervised ML.
- **Practical Applications**: Reinforces skills in data cleaning, feature engineering, and model evaluation.
- **Historical Insight**: Demonstrates how social and demographic factors affected survival during a real-world event.

---

## Project Objectives

- Predict whether a passenger survived the Titanic disaster
- Explore how different factors (class, age, gender, etc.) influenced survival
- Develop an end-to-end ML pipeline covering data preprocessing, feature engineering, and classification modeling

---

## Workflow

1. **Data Collection**  
   Utilized Kaggle’s Titanic dataset containing passenger details and survival labels.

2. **Data Exploration**  
   Analyzed survival rates across categories such as **gender, passenger class, and age groups**.

3. **Data Preprocessing**  
   - Handled missing values (Age, Embarked, Cabin)  
   - Encoded categorical variables (Sex, Embarked)  
   - Created new features (FamilySize, Title extraction)

4. **Feature Engineering**  
   Identified key predictors of survival such as passenger class, gender, and age.

5. **Model Training**  
   Trained using `Logistic Regression` classification model.
   Can use other classification models like:
   - Decision Trees
   - Random Forest
   - Support Vector Machine
   - Gradient Boosting (XGBoost/LightGBM)

7. **Model Evaluation**  
   Compared models using metrics such as **accuracy**, **precision**, **recall**, **F1-score**, and **ROC-AUC**.

---

## Results & Evaluation

The **Random Forest** and **Gradient Boosting** models achieved the best performance, with accuracy exceeding **80%** on the validation set. Key findings:

- **Gender** was the strongest predictor (women had higher survival rates).  
- **Passenger class (Pclass)** significantly influenced survival chances.  
- **Age and family size** played important roles in determining outcomes.  

---

## Key Learnings

- Data preprocessing and feature engineering are critical to improving model performance.  
- Even simple classification models like `Logistic Regression` can achieve strong results with well-prepared features.  
- Historical datasets provide valuable insights while serving as benchmarks for ML practice.  

---

## Contributions

Contributions are welcome. Fork this repository, open issues, or submit pull requests to improve the pipeline or add new modeling approaches.
