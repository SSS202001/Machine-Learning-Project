
# Predictive Modeling for Loan Default Risk Assessment: Leveraging Logistic Regression and Data-Driven Insights

## Description
This project aims to build a predictive model to forecast loan defaults using various machine learning techniques. The dataset used contains information about borrowers and their loans, which is used to train a logistic regression model to predict whether a borrower will default on a loan.


## Dataset


The dataset used in this project is a dataset with 255,347 entries and 18 columns. Each row represents a borrower with various attributes such as age, income, loan amount, credit score, and other related features.
## Data Exploration and Preprocessing

1. Reading the Data: The dataset is read into a Pandas DataFrame.
2. Dropping Unnecessary Columns: The LoanID column is dropped as it does not provide useful information for prediction.
3. Checking Data Types and Missing Values: The data types of each column are checked, and missing values are handled.
4. Categorical Data Inspection: The categorical columns are inspected to understand their distributions.
5. Label Encoding: Categorical columns are converted into numerical data using Label Encoding.
## Feature Engineering

- Correlation Analysis: The correlation between features and the target variable (Default) is analyzed.
- Multicollinearity Check: Variance Inflation Factor (VIF) is calculated to check for multicollinearity among features.
- Data Balancing: Synthetic Minority Over-sampling Technique (SMOTE) is used to balance the dataset.
- Outlier Removal: Isolation Forest is used to remove outliers from the data.
## Model Building and Evaluation

1. Model Selection: Logistic regression is used as the predictive model.
2. Model Training: The model is trained on the preprocessed data.
3. Model Evaluation: The model is evaluated using accuracy, precision, recall, and F1-score. A classification report is generated.
## Results

- Accuracy: 73.55%
- Precision: 76.25%
- Recall: 74.04%
- F1-Score: 75.13%


The model effectively predicts loan defaults, providing valuable insights into risk factors and aiding in better financial decision-making.
## Conclusion

The logistic regression model developed in this project demonstrates a reasonable performance in predicting loan defaults. Significant features impacting loan defaults include age, interest rate, and the presence of a co-signer.
## Acknowledgements

- Dataset Source: This dataset was sourced from Kaggle - https://www.kaggle.com/datasets/nikhil1e9/loan-default
- Libraries and Tools: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, Imbalanced-learn, Statsmodels.
- Inspiration: Inspired by real-world financial risk assessment challenges.
## Appendix

### Data Dictionary
- LoanID: Unique identifier for each loan.
- Age: Age of the borrower.
- Income: Annual income of the borrower.
- LoanAmount: Amount of the loan.
- CreditScore: Credit score of the borrower.
- MonthsEmployed: Number of months the borrower has been employed.
- NumCreditLines: Number of credit lines the borrower has.
- InterestRate: Interest rate on the loan.
- LoanTerm: Term of the loan in months.
- DTIRatio: Debt-to-income ratio of the borrower.
- Education: Education level of the borrower.
- EmploymentType: Type of employment (e.g., full-time, part-time, unemployed).
- MaritalStatus: Marital status of the borrower.
- HasMortgage: Whether the borrower has a mortgage (Yes/No).
- HasDependents: Whether the borrower has dependents (Yes/No).
- LoanPurpose: Purpose of the loan (e.g., auto, business, other).
- HasCoSigner: Whether the loan has a co-signer (Yes/No).
- Default: Target variable indicating whether the borrower defaulted on the loan (0 = No, 1 = Yes).


## Authors

This project was developed by Siddhant Sarnobat as part of Loan Default Prediction Project a Machine Learning Project for educational purpose.


## Contributing

Contributions are always welcome!

I welcome contributions from the community to enhance and expand the analysis of the tourism industry in Europe. Please feel free to submit pull requests or raise issues if you have any suggestions or improvements.


## FAQ

#### Q.What is the purpose of this project?
A. To build a model to predict loan defaults based on borrower data.

#### Q. How can I contribute?
A. You can contribute by submitting a pull request or opening an issue.


## Features

- Predictive modeling using logistic regression.
- Data balancing using SMOTE.
- Outlier removal using Isolation Forest.


## Feedback

I value your feedback! If you have any comments, suggestions, or questions regarding this project, please feel free to reach out to us at siddhantsarnobat20@gmail.com


## 🚀 About Me

Passionate data science student with a focus interested in data analysis and machine learning.


## Github Profile - Introduction

Welcome to my GitHub profile! Here you'll find various data science projects showcasing my skills and interests.
## 🔗 Links
LinkedIn - www.linkedin.com/in/siddhant-sarnobat


## Lessons Learned

- Importance of data preprocessing.
- Handling imbalanced datasets.
- Model evaluation and selection.


## Tech Stack

- Python
- Scikit-learn
- Pandas
- NumPy
## Used By

This project is used by:

- Financial institutions for risk assessment.
- Academic researchers for educational purposes.