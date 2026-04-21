# Cancer-Predication-Regression
cancer-regression-ml/
│
├── data/
│   └── cancer_reg.csv
│
├── notebooks/
│   └── EDA.ipynb
│
├── src/
│   ├── preprocess.py
│   ├── train.py
│   ├── evaluate.py
│
├── models/
│   └── best_model.pkl
│
├── requirements.txt
├── README.md
└── main.py

Cancer Regression ML Project
 Overview

This project predicts cancer-related outcomes (e.g., incidence rates) using multiple regression machine learning models. The goal is to compare model performance and select the best-performing algorithm.

 Dataset
Source: cancer_reg.csv
Features: demographic, socioeconomic, health indicators
Target: continuous cancer rate
 Tech Stack
Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
 Workflow
Data preprocessing (handling missing values, scaling)
Exploratory Data Analysis (EDA)
Model training
Model evaluation
Model comparison
 Models Used
Linear Regression
Decision Tree Regressor
Random Forest Regressor
Support Vector Regressor (SVR)
 Evaluation Metrics
MAE
RMSE
R² Score
 Results

Random Forest performed best due to its ability to capture non-linear relationships and reduce overfitting.
