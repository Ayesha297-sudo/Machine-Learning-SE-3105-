# HCT Survival Prediction using Machine Learning

## Overview
This project implements machine learning models to predict survival outcomes for patients undergoing Hematopoietic Cell Transplantation (HCT). The dataset includes key clinical factors such as age, donor characteristics, comorbidities, and conditioning intensity, which influence patient survival.

## Methodology

### 1. Data Preprocessing
- **Handling Missing Values:** Imputation techniques (median/mode filling).  
- **Outlier Detection & Treatment:** IQR method for numerical features.  
- **Feature Encoding:** Label encoding for categorical features.  
- **Feature Scaling:** Standardization using `StandardScaler`.  

### 2. Model Training
We experimented with multiple machine learning models, including:  
- **Logistic Regression**  
- **Decision Tree Classifier**  
- **Naïve Bayes (GaussianNB & BernoulliNB)**  
- **K-Nearest Neighbors (KNN)**  
- **Random Forest Classifier**  
- **Voting Classifier (Ensemble Method)**  

### 3. Hyperparameter Tuning
- Used **Grid Search Cross-Validation** to optimize hyperparameters for best model performance.  

### 4. Model Evaluation
We assessed model performance using:  
- **Accuracy Score**  
- **Precision, Recall & F1-Score**  
- **ROC-AUC Curve**  
- **Confusion Matrix**  

## Key Findings
✔ **Younger patients** exhibited higher survival probabilities.  
✔ **Primary disease** significantly affects survival rates.  
✔ **Comorbidities** (e.g., diabetes) reduce survival chances.  
✔ **Random Forest & Voting Classifier** performed best among models.  

## Future Work
🔹 Explore **deep learning models** like Neural Networks.  
🔹 Optimize **ensemble learning techniques**.  
🔹 Deploy the model as a **web application** using Flask/Django.  
🔹 Enhance explainability with **SHAP values**.  


