# Olympic Medal Prediction

## Overview

This project explores **predictive modeling of Olympic medal counts** using historical data. The goal is to estimate how many medals a country will win in upcoming Olympic games based on past performance and relevant country-level features.  

A **Linear Regression model** was applied to analyze the relationship between historical factors and medal counts. This serves as an introductory supervised machine learning project for regression tasks.

---

## Project Workflow

1. **Hypothesis Formation**  
   Assumed that a country’s historical performance and attributes (e.g., past medals, participation, resources) can help predict future medal counts.

2. **Data Collection**  
   Used the `teams.csv` dataset, containing country-level Olympic participation and medal statistics.

3. **Data Exploration**  
   - Visualized medal distributions across countries and years  
   - Identified correlations between historical data and medal counts  

4. **Data Preparation**  
   - Handled missing values  
   - Reshaped features for regression modeling  
   - Scaled numerical features for consistency  

5. **Model Development**  
   - Implemented **Linear Regression** using scikit-learn  
   - Defined performance metric (Mean Squared Error)  
   - Split dataset into training and testing sets  

6. **Evaluation**  
   - Measured prediction accuracy  
   - Interpreted coefficients to understand feature importance  

---

## Results

- **Linear Regression** captured general trends in medal prediction but struggled with outliers (countries with extreme medal counts like the USA, China, Russia).  
- Model performance showed that **historical medals** are the strongest predictor of future success.  
- This project highlights both the **potential and limitations** of linear models in sports analytics.

---
