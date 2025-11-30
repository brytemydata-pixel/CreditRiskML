**Unified Synthetic Financial Risk Dataset**

This directory contains the synthetic dataset used to train and evaluate the machine learning models in this project. It simulates a realistic financial environment containing:

Customer-level information

Account-level attributes

Transaction-level behaviour

Risk indicators for credit default, fraud, and AML

Although fully synthetic, the dataset reflects common patterns from Canadian retail banking and is suitable for education, analytics research, and model prototyping.


📌 Dataset Files
File	Description
merged_financial_data.csv	Combined dataset containing customer, account, and transaction attributes for multi-risk modeling.

📌 Key Columns
Customer Features

Age

Income

Employment status

Province

Account tenure

Mortgage flag

Account/Behavioral Features

Credit utilization

Delinquency indicators

Credit limit

Balance

Spending categories

Transaction frequency

Transaction Features

Amount

Channel (POS, ATM, online, mobile)

Merchant category

International flag

Time of day indicators

Device ID

Transfer patterns

Target Variables

credit_default_flag

is_fraud

is_aml_suspicious


📌 Intended Use Cases

This dataset is designed for research and prototyping in:

Credit risk modeling

Fraud detection

AML behavioral analysis

Imbalanced classification techniques

Threshold optimization

Explainability and model governance


📌 Recommended Models

This project uses:

Logistic Regression (explainability, regulatory alignment)

XGBoost (high performance, nonlinear pattern detection)

Both models are appropriate for applied financial risk analytics.

📌 Source

This dataset is synthetically generated using Python/Google Colab for educational and analytical purposes only. No real customer or institution data is used.
