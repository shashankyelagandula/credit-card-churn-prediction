# Credit Card Churn Prediction

## Project Title
**Predicting Credit Card Account Cancellations**

## Introduction
This project is an individual assignment focused on applied data science using a real dataset. The goal is to explore factors leading to credit card account cancellations and to develop machine learning algorithms to predict the likelihood of future cancellations.

## Data
The `credit_card_df` data frame contains information on over 4,000 customers of a U.S. bank. The bank aims to identify customers at risk of canceling their accounts to minimize financial losses due to declining revenue from account closures.

### Key Questions Addressed:
- **What factors are associated with customers closing their credit card accounts?**
- **Is it possible to predict account closure, and if so, what is the prediction accuracy and expected cost of errors?**
- **What actions or policies can the bank implement to reduce customer churn?**

### Outcome Variable
The `customer_status` variable indicates whether a customer closed their account (`closed_account`, the positive class) or is active.

## Data Definitions

| Variable | Definition | Data Type |
|----------|------------|-----------|
| `customer_status` | Customer status (closed account or active) | Factor |
| `age` | Customer age | Numeric |
| `dependents` | Number of dependents in household | Numeric |
| `education` | Customer education level | Factor |
| `marital_status` | Marital status | Factor |
| `employment_status` | Employment status | Factor |
| `income` | Annual income (US Dollars) | Numeric |
| `card_type` | Type of credit card | Factor |
| `months_since_first_account` | Months since first credit card account activated | Numeric |
| `total_accounts` | Total accounts (credit, checking, and savings) | Numeric |
| `months_inactive_last_year` | Months without credit card activity last year | Numeric |
| `contacted_last_year` | Number of times contacted last year by sales representatives | Numeric |
| `credit_limit` | Current credit limit | Numeric |
| `utilization_ratio` | Average monthly balance to credit limit | Numeric |
| `spend_ratio_q4_q1` | Ratio of total Q4 to Q1 spending last year | Numeric |
| `total_spend_last_year` | Total amount charged last year | Numeric |
| `transactions_last_year` | Number of transactions last year | Numeric |
| `transaction_ratio_q4_q1` | Ratio of total Q4 to Q1 transactions last year | Numeric |

## Recommendations

### 📊 Usage Ratio Monitoring
Proactively monitor usage ratios, especially for accounts with ratios less than 25%, to identify and engage at-risk clients. This helps lower acquisition costs and increases customer engagement and retention.

### 🎓 Improved Customer Education
Provide financial literacy classes or resources to customers with associate's and master’s degrees to address reasons for account closure. This aims to improve client satisfaction and loyalty, fostering long-lasting partnerships.
