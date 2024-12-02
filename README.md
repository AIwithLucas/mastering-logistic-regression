## Objective: Mastering Logistic Regression

### 1. Theoretical Mastery

    - Sigmoid function & its properties
    - Logit function and probability interpretation
    - Cost function (log-loss)
    - Gradient descent optimization for logistic regression

### 2. Algorithmic Implementation

    - Logistic Regression from scratch
    - Logistic Regression with libraries

### 3. Performance Analysis

    - Confusion Matrix
    - Precision, Recall, F1-score
    - ROC Curve and AUC

### 4. Advanced Logistic Regression

    - Regularization techniques (L1 & L2)
    - ElasticNet
    - Feature Engineering & selection
    - Class Imbalance Handling
    - Handling Non-Linear Decision Boundaries
    - Bayesian Logistic Regression

---

# German Credit Risk Dataset

- widely used in ML & Stats analysis to predict loan default status
- contains info about individuals and their credit profiles
- classify whether a loan applicant likely to default or not

## Dataset Description

    - 1000 samples
    - 20 features

### Target Variable: Risk - Good Credit vs Bad Credit

### Features

| Feature Name      | Type        | Description                                                                |
| ----------------- | ----------- | -------------------------------------------------------------------------- |
| Age               | Numerical   | Age of the applicant in years.                                             |
| Sex               | Categorical | Gender of the applicant.                                                   |
| Job               | Categorical | Employment type or job category (e.g., skilled, unskilled, unemployed).    |
| Housing           | Categorical | Type of housing (e.g., Own, Rent, Free).                                   |
| Saving Accounts   | Categorical | Amount saved in accounts (e.g., Little, Moderate, Rich).                   |
| Checking Accounts | Categorical | Status of checking account (e.g., Little, Moderate, Rich).                 |
| Credit Amount     | Numerical   | The loan amount requested by the applicant.                                |
| Duration          | Numerical   | Loan repayment duration in months.                                         |
| Purpose           | Categorical | Purpose of the loan (e.g., Car, Education, Business).                      |
| Installment Rate  | Numerical   | Loan installment as a percentage of disposable income.                     |
| Other Debtors     | Categorical | Presence of other debtors or guarantors.                                   |
| Residence Since   | Numerical   | Duration (in years) of the applicant's residence at their current address. |
| Property          | Categorical | Type of property owned by the applicant.                                   |
| Credit History    | Categorical | Record of previous credit activity.                                        |
| Telephone         | Categorical | Indicates if the applicant has a telephone (Yes/No).                       |
| Foreign Worker    | Categorical | Whether the applicant is a foreign worker (Yes/No).                        |

### Applications in Logistic Regression

The dataset is particularly useful for binary classification problems like logistic regression.

    1. Predict Loan Defaults: Determine the likelihood of an applicant defaulting based on their credit profile.
    2. Feature Engineering: Extract relevant features and handle categorical variables using techniques like one-hot encoding.
    3. Model Evaluation: Analyze model performance using metrics such as accuracy, precision, recall, and AUC-ROC.
