# Bank-Fraud-Detection
This dataset is designed for Bank Fraud Detection and Machine Learning classification projects. It contains financial transaction records that can be used to analyze transaction behavior, identify fraudulent patterns, perform exploratory data analysis (EDA), and build machine learning models for fraud detection.


Dataset Overview

Each row represents an individual financial transaction. The dataset contains information about the transaction type, transaction amount, sender and receiver account balances, and fraud indicators.

The main objective is to predict whether a transaction is fraudulent (isFraud = 1) or legitimate (isFraud = 0).

Features
step — Represents the time step of the transaction. In this dataset, each step corresponds approximately to one hour.
type — Type of transaction, such as PAYMENT, TRANSFER, CASH_OUT, CASH_IN, or DEBIT.
amount — Amount of money involved in the transaction.
nameOrig — Identifier of the account initiating the transaction.
oldbalanceOrg — Account balance of the sender before the transaction.
newbalanceOrig — Account balance of the sender after the transaction.
nameDest — Identifier of the receiving account.
oldbalanceDest — Account balance of the destination before the transaction.
newbalanceDest — Account balance of the destination after the transaction.
isFraud — Target variable indicating whether the transaction is fraudulent.
0 = Legitimate transaction
1 = Fraudulent transaction
isFlaggedFraud — Indicates whether the transaction was flagged by an existing fraud-detection rule.

Project Goal

The goal of this project is to demonstrate an end-to-end data science workflow for detecting fraudulent bank transactions, from data exploration and preprocessing to machine learning model development and evaluation.
