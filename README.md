# Credit Card Approval Prediction

##Google Colab Link

https://colab.research.google.com/drive/1qB78DD3H2zSchQCnn3lGmQxVE3DIhfKj?usp=sharing

## Overview
This project focuses on improving credit risk assessments through advanced machine learning algorithms. Our aim was to develop a model capable of accurately differentiating between "good" and "bad" credit risks, based on a wide range of borrower data that extends beyond conventional financial indicators.

## Technologies Used
- **Programming Languages & Libraries:** Python (with scikit-learn, pandas, numpy)
- **Data Balancing Technique:** SMOTE for handling class imbalance
- **Platform:** Google Colab

## Methodology

### Data Preprocessing
- **Cleaning & Feature Engineering:** Rigorous data cleaning and feature engineering were performed, including the merging of two key datasets using unique identifiers. This created a solid analytical foundation.
- **Categorical Integration:** Anomalies were addressed, and categorical variables were integrated through one-hot encoding, preparing the data for machine learning.

### Model Development
- **Classifier Application:** A variety of machine learning classifiers were tested, including Logistic Regression, Decision Trees, SVM, and Random Forest.
- **Optimization:** Hyperparameter tuning was conducted using GridSearchCV, and SMOTE was utilized to address class imbalance, ensuring model fairness and accuracy.

### Evaluation and Insights
- **Comparative Analysis:** The models were evaluated based on accuracy, precision, recall, F1-score, and ROC-AUC scores. Logistic Regression was identified as the most effective model due to its balanced precision and recall rates.

## Outcome
The project successfully developed a predictive model that enhances the accuracy of credit risk evaluations. This model reduces the likelihood of loan defaults and supports more informed lending decisions, contributing to the advancement of credit risk assessment processes.

