# Prediciting_Loan_defaulters_using_Logistic_Regression

Loan Default Prediction
This project predicts loan default using Logistic Regression. The model classifies whether a loan will default based on features such as income, credit score, loan amount, and more.

How to Run
Upload the Dataset:

Ensure your dataset is in CSV format with columns like LoanID, Age, Income, LoanAmount, CreditScore, etc.

Upload your CSV file to Google Colab.

Run the Script:

The script will preprocess the data (standard scaling for numerical features and one-hot encoding for categorical features), train a logistic regression model, and evaluate it using accuracy and a confusion matrix.

Code Workflow
Data Preprocessing:

Drops the LoanID and Default columns from the features.

Standardizes numerical features and applies one-hot encoding to categorical features.

Model Training:

The data is split into training and testing sets (80%-20% split).

A logistic regression model is trained using the processed data.

Evaluation:

The model’s accuracy is calculated.

A confusion matrix is plotted to visualize the model's performance.

Logistic Regression
Logistic Regression is a statistical method used for binary classification problems, where the goal is to predict one of two possible outcomes (e.g., default or no default on a loan). Unlike linear regression, which predicts continuous values, logistic regression uses a logistic function to model the probability of a binary response.

The logistic function, also called the sigmoid function, outputs values between 0 and 1. The output represents the probability of a particular outcome (e.g., the probability of a loan defaulting). The logistic regression model uses a weighted sum of the input features and applies the sigmoid function to predict the probability of default.

The model is trained to minimize the error in predicting the default status, and once trained, it can classify new data based on learned patterns.

