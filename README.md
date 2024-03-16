# Machine_Learning_Homework

Purpose - The analysis aims to develop machine learning models to predict credit risk using historical lending activity data.

Financial Information - The data includes features such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The target variable is "loan_status," where 0 represents a healthy loan and 1 represents a high-risk loan.

Variables - The target variable "loan_status" was predicted using various financial features.

Machine Learning Process - The analysis involved data preprocessing, model training, and evaluation. Logistic Regression was used as the primary classifier. Additionally, the resampling technique RandomOverSampler was employed to address class imbalance. Specifically, the training data for risky loans. 

Machine Learning Model 1:

Balanced Accuracy Score: 0.965
Precision (Class 0): 1.00
Precision (Class 1): 0.84
Recall (Class 0): 0.99
Recall (Class 1): 0.94
Machine Learning Model 2:

Balanced Accuracy Score: 0.993
Precision (Class 0): 1.00
Precision (Class 1): 0.84
Recall (Class 0): 0.99
Recall (Class 1): 0.99

Summary: Model 2 performs best, showing higher recall for high-risk loans. This is crucial for identifying potential credit risks effectively. In the context of credit risk assessment, it is more important to correctly predict high-risk loans. Model 2, with its improved performance in identifying high-risk loans, is recommended for this task.