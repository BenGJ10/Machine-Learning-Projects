# Traffic Accident Prediction using Supervised Learning

## 📌 Project Overview
This project focuses on predicting road traffic accidents using supervised learning techniques. The primary objective is to analyze accident data and build machine learning models to predict accident severity or occurrence. The study involves **Support Vector Machines (SVM)** as the primary model, along with comparisons to **Random Forest** and **XGBoost**.

### 🔍 Research Significance
Road traffic accidents are a major global concern, leading to loss of life and property. This research aims to utilize machine learning for:
- Identifying key factors contributing to accidents
- Predicting accident severity
- Enhancing road safety through data-driven insights

---

## 📊 Dataset Information
- **Dataset Name:** Traffic Accident Prediction Dataset  
- **Size:** Over 2000 rows  
- **Attributes:** Time of accident, weather conditions, road surface conditions, severity levels, etc.  
- **Source:** Open-source road accident dataset  
- **Preprocessing Steps:** Handling missing values, categorical encoding, feature selection  

---

## 🏗️ Implementation Steps

### 1️⃣ Exploratory Data Analysis (EDA)
- Conducted **univariate** and **bivariate analysis**
- Visualized accident trends using **bar charts, heatmaps, and scatter plots**
- Identified **missing values and outliers**

### 2️⃣ Data Preprocessing
- **Missing value treatment:** Replaced missing values with mean/median/mode
- **Encoding categorical variables:** Applied **label encoding** for categorical features
- **Feature selection:** Removed highly correlated and irrelevant features

### 3️⃣ Feature Engineering
- **Scaling:** Standardized numerical features  
- **Handling class imbalance:** Used **SMOTE (Synthetic Minority Over-sampling Technique)** to balance data  

### 4️⃣ Model Training & Evaluation
- **Trained an SVM model** for accident prediction  
- **Compared with Random Forest and XGBoost**  
- **Performance Metrics Used:** Accuracy, Precision, Recall, F1-Score, ROC-AUC Curve  

### 5️⃣ Hyperparameter Tuning
- Optimized model parameters using **GridSearchCV**
- Selected best parameters for improved performance  

---

## 📈 Model Performance Comparison

| Model         | Accuracy | Precision | Recall | F1-Score |
|--------------|----------|-----------|--------|----------|
| SVM          | XX.XX%   | XX.XX%    | XX.XX% | XX.XX%   |
| Random Forest| XX.XX%   | XX.XX%    | XX.XX% | XX.XX%   |
| XGBoost      | XX.XX%   | XX.XX%    | XX.XX% | XX.XX%   |

---

## 🔬 Key Research Findings
- **SVM performed competitively** but did not significantly outperform other models  
- **Feature selection and resampling were crucial** for handling imbalanced data  
- **Advanced supervised learning techniques did not drastically improve accuracy**  
- **Random Forest and XGBoost performed slightly better than SVM** in terms of overall metrics  

---

## 🚀 How to Run the Project

### 🔹 Clone the Repository
```bash
git clone https://github.com/yourusername/traffic-accident-prediction.git
cd traffic-accident-prediction
```

### 🔹 Install Dependencies
```bash
pip install -r requirements.txt
```

### 🔹 Run the Jupyter Notebook
```bash
jupyter notebook Traffic_Accident_Prediction.ipynb
```

## 🔚 Conclusion
The project evaluates the effectiveness of SVM for traffic accident prediction and compares it with alternative models. While SVM provides competitive accuracy, Random Forest and XGBoost performed slightly better in some aspects.

Further improvements can be made by:

Incorporating deep learning models

Using more advanced feature engineering techniques

Gathering more extensive datasets