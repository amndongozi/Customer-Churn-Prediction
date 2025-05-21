# Customer-Churn-Prediction

📊 Customer Churn Prediction and Inference
This project explores customer churn behavior in a telecommunications company using two complementary approaches: prediction and inference. The goal is to both understand the key drivers of churn (inference) and build accurate models to identify high-risk customers before they leave (prediction).

🧠 Objective
Inference: Identify and explain which customer features are most associated with churn.

Prediction: Develop machine learning models that accurately predict churn likelihood for each customer.

🔍 Project Overview
Dataset: Telco Customer Churn Dataset
Target Variable: Churn (Yes/No)

Workflow:
Data Cleaning & Preprocessing

Converted TotalCharges to numeric

Handled missing values using imputation

Dropped irrelevant identifiers (customerID)

Exploratory Data Analysis (EDA)

Churn distribution visualizations

Feature summaries and value counts

Identification of potential churn indicators

Two-step Analytical Approach

🔎 Inference:

Logistic Regression (interpretable coefficients & odds ratios)

Feature association analysis

🤖 Prediction:

Decision Tree

k-Nearest Neighbors (k-NN)

Logistic Regression (for classification)

Model selection via cross-validation

Evaluation with accuracy, ROC curves, precision-recall metrics

📈 Visual Insights
Churn is moderately imbalanced (~73% No, ~27% Yes)

Service tenure, contract type, payment method, and monthly charges show strong relationships with churn behavior


🧰 Tools & Libraries
Python (Jupyter Notebook)

pandas, numpy – Data wrangling

matplotlib, seaborn – Visualization

scikit-learn – Modeling & evaluation

📌 Key Findings
Customers with month-to-month contracts, electronic checks, and short tenure are more likely to churn.

Logistic regression helped interpret key drivers using odds ratios.

Decision Trees and k-NN provided competitive prediction performance, with trade-offs in interpretability vs. flexibility.

