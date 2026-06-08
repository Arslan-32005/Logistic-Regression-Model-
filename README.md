"Logistic Regression Workflow with Preprocessing"  
This repository demonstrates a complete machine learning pipeline using logistic regression for classification tasks. It includes:
Data cleaning: Handling missing values, removing duplicates, and dropping irrelevant columns.
Imputation: Filling missing categorical values with mode and numeric values with median.
Encoding: Converting categorical features into numeric format using LabelEncoder.
Feature engineering: Simplifying categories (e.g., grouping countries into broader classes).
Train‑test split: Dividing the dataset into training and testing sets with stratification to preserve class balance.
Scaling: Standardizing numerical features using StandardScaler for better model convergence.
Model training: Logistic regression with class imbalance handling and extended iterations for stability.
Evaluation: Measuring performance with accuracy, precision, recall, and F1 score to capture trade‑offs between majority and minority classes.
This repo serves as a practical reference for applying logistic regression to real‑world datasets, showing how preprocessing steps directly impact model performance.
