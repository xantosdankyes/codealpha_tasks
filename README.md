# Credit Scoring Model

CodeAlpha Machine Learning Internship

Project Overview

This project develops a machine learning-based Credit Scoring Model to predict the creditworthiness of loan applicants using historical financial data.

The objective is to help financial institutions assess the risk associated with loan applications and make informed lending decisions.

⸻

Dataset

The dataset contains information about applicants including:

* Age
* Income
* Home Ownership
* Employment Length
* Loan Intent
* Loan Grade
* Loan Amount
* Interest Rate
* Credit History Length
* Previous Default History

Target Variable:

* loan_status
    * 0 = Low Risk
    * 1 = High Risk

⸻

Data Preprocessing

The following preprocessing steps were performed:

* Missing value handling
* Label Encoding of categorical features
* Feature selection
* Train-Test Split (80%-20%)

⸻

Machine Learning Models Used

Logistic Regression

* Accuracy: 82.92%
* Precision: 70.54%
* Recall: 39.45%
* F1 Score: 50.60%

Decision Tree

* Accuracy: 88.46%
* Precision: 72.84%
* Recall: 76.47%
* F1 Score: 74.61%

Random Forest

* Accuracy: 92.97%
* Precision: 96.43%
* Recall: 70.93%
* F1 Score: 81.74%
* ROC-AUC: 93.49%

⸻

Best Model

Random Forest achieved the highest performance and was selected as the final model.

⸻

Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

⸻

Conclusion

The Random Forest classifier demonstrated strong predictive performance for credit risk assessment and can be used to support financial decision-making processes.
