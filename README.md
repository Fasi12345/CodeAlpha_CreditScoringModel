CodeAlpha_Credit_Scoring_Model
---
Project Overview
---
This project aims to predict an individual's creditworthiness using past financial history. Classification models such as Logistic Regression, Decision Tree, and Random Forest were employed to identify potential credit risks.

Dataset Description
The dataset includes various financial attributes of users, such as:

Number of inquiries

Payment history

Account utilization

Delinquency indicators

Total loans & balances

All features are numerical, eliminating the need for categorical encoding.

Machine Learning Models Used
Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Each model was evaluated using:

Accuracy

Precision

Recall

F1-Score

ROC-AUC Score

Exploratory Data Analysis (EDA)
Distribution of financial attributes

Correlation heatmap

Credit risk pattern analysis

Outlier and imbalance inspection

Final Insights
Loan Delinquency and High Credit Utilization were key indicators of credit risk.

Random Forest Classifier gave the best performance with a balanced accuracy and AUC.

Model performance was visualized using ROC-AUC curves for comparison.

Project Structure

CodeAlpha_Credit_Scoring_Model
Task_01_Credit_Scoring_Model.ipynb
visualizations/
README.md

How to Run
Clone this repository

Open the .ipynb file using Jupyter Notebook or Google Colab

Run all cells to reproduce results

Conclusion
This project provides a strong foundation for automated credit scoring systems, helping financial institutions identify and reduce risk in lending.
