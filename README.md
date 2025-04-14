Names: Dane Pastor, Zachary Kinnaman

Project Proposal: Predicting stress levels in individuals from smart watch data.
Link to research
Project Overview
This project aims to identify self-assessed stress levels from 1 - 10 in individuals given parameters tracked by smart watches. Aims to predict from several factors such as sleep duration, average heart rate, activity levels, and blood oxygen levels.
Machine Learning Approach
1. Data Preprocessing
Download and clean the dataset from Kaggle (Null and error values present).
Standardize expression levels using Z-score normalization.
Create feature matrix accounting for different data types (Specifically one hot encoders for categorical data)
2. Exploratory Data Analysis (EDA)
Check class distribution (low vs medium vs high stress).
Identify parameters with high variance across the dataset.
Visualize expression differences using heatmaps.
3. Modeling & Training
Baseline Model: Use regression modeling to predict stress levels.
Optimize hyperparameters for prediction accuracy.
Advanced Models:
Support Vector Machines (SVM) for high-dimensional parameter classification.
K means clustering for classifying stress levels.
4. Evaluation & Interpretation
Evaluate models using ROC-AUC, precision, and recall.
Use SHAP values to determine the most influential parameters.
Feature importance analysis to suggest which aspects are most correlated to stress.
Answer the question - Is self reporting stress levels consistent enough for us to answer our previously described questions with this data set? 
Work Breakdown
Task
Responsible Team Member
Data acquisition & preprocessing
Dane
Exploratory Data Analysis (EDA)
Zack
Feature engineering & PCA
Dane
Baseline ML model (Decision Tree)
Zack
Advanced ML models (XGBoost, Neural Network)
Dane
SVM modeling
Zack
Model evaluation & interpretation
Both
Writing results & conclusions
Both



