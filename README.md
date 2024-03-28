# credit-card-approval

Objective: Leveraged advanced machine learning algorithms to enhance the credit risk assessment process, aiming for a model that accurately identifies "good" and "bad" credit risks using comprehensive borrower data beyond traditional financial indicators.

Technologies Used: Python, scikit-learn, pandas, numpy, SMOTE (for class imbalance handling), Google Colab.

Methodology:

Data Preprocessing: Employed meticulous data cleaning, feature engineering, and merging of two key datasets via unique identifiers to create a robust framework for analysis. Addressed anomalies and integrated categorical variables through one-hot encoding to prepare the dataset for machine learning applications.
Model Development: Applied various machine learning classifiers including Logistic Regression, Decision Trees, SVM, and Random Forest. Utilized GridSearchCV for hyperparameter optimization and incorporated SMOTE to address class imbalance, enhancing model fairness and accuracy.
Evaluation and Insights: Conducted a comparative analysis using accuracy, precision, recall, F1-score, and ROC-AUC scores to identify the most effective model. The logistic regression model was selected for its balanced performance in precision and recall, particularly valuable for credit risk assessment.
Outcome: Developed a predictive model that significantly improves the accuracy of credit risk evaluations, reducing the likelihood of loan defaults and enabling more informed lending decisions.
