Names: Dane Pastor, Zachary Kinnaman

Project Proposal 2: Predicting Malathion Resistance in Culex quinquefasciatus Mosquitoes (GSE206489)
Link to research
Project Overview
This project aims to identify genetic markers associated with resistance to Malathion, an insecticide used for mosquito control. Using machine learning, we will classify mosquitoes as either resistant or non-resistant based on transcriptome data.
Machine Learning Approach
1. Data Preprocessing
Download and clean the dataset from the GEO database.
Standardize expression levels using Z-score normalization.
Apply dimensionality reduction techniques such as PCA or t-SNE.
2. Exploratory Data Analysis (EDA)
Check class distribution (resistant vs. non-resistant).
Identify genes with high variance across the dataset.
Visualize expression differences using heatmaps.
3. Modeling & Training
Baseline Model: Use Decision Trees to classify resistance based on gene expression.
Optimize hyperparameters for prediction accuracy.
Advanced Models:
Support Vector Machines (SVM) for high-dimensional gene expression classification.
Possibly in addition: Neural Networks (Feed-forward MLP) to predict resistance.
4. Evaluation & Interpretation
Evaluate models using ROC-AUC, precision, and recall.
Use SHAP values to determine the most influential genes.
Feature importance analysis to suggest candidate genes for further biological validation.
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



