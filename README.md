# Project Proposal: Predicting Stress Levels in Individuals from Smart Watch Data

**Team Members:**  
- Dane Pastor  
- Zachary Kinnaman  

**Link to Research:** _(add hyperlink here)_

---

## Project Overview

This project aims to identify self-assessed stress levels (on a scale from 1 to 10) in individuals using parameters tracked by smart watches. The model will predict stress levels based on several physiological and behavioral metrics, including:

- Sleep duration  
- Average heart rate  
- Activity levels  
- Blood oxygen levels  

---

## Machine Learning Approach

### 1. Data Preprocessing

- Download and clean the dataset from Kaggle (note: dataset contains null and error values).  
- Standardize expression levels using **Z-score normalization**.  
- Create a feature matrix accounting for different data types (e.g., use **one-hot encoders** for categorical variables).  

### 2. Exploratory Data Analysis (EDA)

- Check class distribution (low vs medium vs high stress).  
- Identify parameters with high variance across the dataset.  
- Visualize expression differences using **heatmaps**.  

### 3. Modeling & Training

- **Baseline Model:**  
  - Use regression modeling to predict stress levels.  
  - Optimize hyperparameters to improve prediction accuracy.

- **Advanced Models:**  
  - **Support Vector Machines (SVM)** for high-dimensional parameter classification.  
  - **K-means clustering** for classifying stress levels.

### 4. Evaluation & Interpretation

- Evaluate models using metrics such as **ROC-AUC**, **precision**, and **recall**.  
- Use **SHAP values** to determine the most influential parameters.  
- Conduct **feature importance analysis** to identify which features are most correlated with stress.  
- Address the question:  
  _“Is self-reporting stress levels consistent enough to allow meaningful predictions with this dataset?”_

---

## Work Breakdown

| Task                               | Responsible Team Member |
|------------------------------------|--------------------------|
| Data Wrangling and Cleaning        | Dane                     |
| Data Preprocessing                 | Dane                     |
| Exploratory Data Analysis (EDA)    | Zack                     |
| Ridge Regression Modelling         | Dane                     |
| Feature Analysis & PCA             | Dane                     |
| Baseline ML model (Decision Tree)  | Zack                     |
| Advanced ML models (XGBoost, NN)   | Dane                     |
| SVM modeling                       | Zack                     |
| Model evaluation & interpretation  | Both                     |
| Writing results & conclusions      | Both                     |
