Task 01: Credit Scoring Model using Classification Algorithms
---
This project is part of my Data Science Internship at CodeAlpha, where I built a Credit Scoring Model to assess the creditworthiness of individuals using classification techniques such as Logistic Regression, Decision Tree, and Random Forest.
---
Objective
To predict whether an individual is likely to default on credit using historical financial behavior and account-related features.

Dataset
Name: Credit Scoring Dataset

Features:

Financial history (loan counts, balances, payment history)

Credit inquiries & utilization percentages

Account activity timeline

Target: TARGET — 1 for Defaulter, 0 for Non-Defaulter

Technologies Used
Python

Pandas

Scikit-learn

Seaborn / Matplotlib

Jupyter Notebook

Steps Performed
✅ 1. Data Exploration
Checked dataset structure, types, null values, and descriptive statistics

Visualized key patterns using bar plots, heatmaps, and distribution plots

✅ 2. Data Preprocessing
Verified all columns were numerical

Checked for imbalance in the target class

Standardized features using StandardScaler

Performed Train-Test split (80:20)

✅ 3. Model Building
Trained Logistic Regression, Decision Tree, and Random Forest classifiers

Compared performance using classification metrics

✅ 4. Evaluation
Accuracy, Precision, Recall, F1-Score, ROC-AUC

Plotted Confusion Matrix and ROC Curves for each model

✅ Results
Random Forest Classifier performed the best overall

ROC-AUC Score: 0.92

Accuracy: 90%+ on test set

Key Indicators of default risk:

High loan utilization

Frequent inquiries

Past late payments

✅ Insights
Individuals with multiple recent inquiries and high utilization are at higher risk

Past payment issues strongly affect creditworthiness predictions

Random Forest was most effective at balancing recall and precision

Conclusion
This project provides a strong foundation for automated credit scoring systems, helping financial institutions identify and reduce risk in lending.
