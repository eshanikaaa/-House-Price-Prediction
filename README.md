# This project uses the Kaggle dataset House Prices - Advanced Regression Techniques to build a predictive model that estimates house prices based on various features.

# Dataset Overview
Train data: 1460 rows × 81 columns,
Test data: 1459 rows × 80 columns,
Target variable: SalePrice

# Data Preprocessing & Feature Engineering
Key transformations applied:
Handling missing values (numeric: mean, categorical: mode or 'None'),
One-hot encoding and label encoding of categorical features,
Feature engineering (e.g., TotalSF, AgeOfHouse, RemodAge),
Dropped irrelevant or sparse columns,
Removed or capped extreme outliers,
Saved clean data to train_preprocessed.csv and test_preprocessed.csv

# Model Used
Algorithm: Ridge Regression,
Validation Technique: Train-test split (80/20),
Evaluation Metric: Root Mean Squared Error (RMSE),
Validation RMSE: ~29899.68
