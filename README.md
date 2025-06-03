Bank Customer Churn Analysis with Several Models Including Deep Learning

Overview
This project analyzes a bank's customer churn dataset and builds machine learning models to predict whether a customer will leave (churn). The notebook includes data preprocessing, feature engineering, class balancing with SMOTE, model building, and evaluation using several classification algorithms.

Dataset
Source: Provided by instructor (not open-source)

Size: 10,000 records × 12 features

Target: churn (binary: 1 = churned, 0 = retained)

Features:

Demographic: age, gender, country

Account info: balance, products_number, tenure, credit_card, active_member

Financial: estimated_salary

Project Steps
Data Loading & Exploration

Basic stats and visualizations

Checked data distribution, outliers, and class imbalance

Preprocessing

Encoding categorical variables

Standardizing numerical features

Handling missing values

SMOTE to balance classes

Modeling

Logistic Regression

Support Vector Machine (SVM)

Random Forest

Gradient Boosting

Deep Learning (if applicable in later cells)

Evaluation

Accuracy, precision, recall, F1-score

Confusion matrix

ROC & AUC curves

Precision-Recall curve

Requirements
Install the necessary packages with:

bash
Copy
Edit
pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn joblib
If using Google Colab:

python
Copy
Edit
from google.colab import files
uploaded = files.upload()
How to Run
Upload the notebook to your local environment or Google Colab.

Upload the dataset when prompted (if using Colab).

Run all cells sequentially to train and evaluate the models.

Results Summary
Each model’s performance is compared based on accuracy and AUC. The best-performing model is highlighted with justification based on metrics.

Author
Roman – MS in Data Science, National University
Project completed as part of coursework in machine learning, AI, and optimization.