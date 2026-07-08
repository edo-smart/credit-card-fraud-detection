 
 # Data Dictionary

## Dataset
Credit Card Fraud Detection Dataset

## Dataset Overview

This dataset contains credit card transactions made by European cardholders in September 2013.

It contains:

- 284,807 transactions
- 31 columns
- Binary target variable (Class)

Due to confidentiality, most features have been transformed using Principal Component Analysis (PCA).

## Data Dictionary

| Column | Data Type | Description |
|---------|----------|-------------|
| Time | Numeric | Time elapsed in seconds from the first transaction |
| V1 | Numeric | PCA-transformed feature |
| V2 | Numeric | PCA-transformed feature |
| V3 | Numeric | PCA-transformed feature |
| V4 | Numeric | PCA-transformed feature |
| V5 | Numeric | PCA-transformed feature |
| V6 | Numeric | PCA-transformed feature |
| V7 | Numeric | PCA-transformed feature |
| V8 | Numeric | PCA-transformed feature |
| V9 | Numeric | PCA-transformed feature |
| V10 | Numeric | PCA-transformed feature |
| V11 | Numeric | PCA-transformed feature |
| V12 | Numeric | PCA-transformed feature |
| V13 | Numeric | PCA-transformed feature |
| V14 | Numeric | PCA-transformed feature |
| V15 | Numeric | PCA-transformed feature |
| V16 | Numeric | PCA-transformed feature |
| V17 | Numeric | PCA-transformed feature |
| V18 | Numeric | PCA-transformed feature |
| V19 | Numeric | PCA-transformed feature |
| V20 | Numeric | PCA-transformed feature |
| V21 | Numeric | PCA-transformed feature |
| V22 | Numeric | PCA-transformed feature |
| V23 | Numeric | PCA-transformed feature |
| V24 | Numeric | PCA-transformed feature |
| V25 | Numeric | PCA-transformed feature |
| V26 | Numeric | PCA-transformed feature |
| V27 | Numeric | PCA-transformed feature |
| V28 | Numeric | PCA-transformed feature |
| Amount | Numeric | Transaction amount |
| Class | Integer | Target variable (0 = Legitimate, 1 = Fraudulent) |

## Target Variable

### Class

0 → Legitimate Transaction

1 → Fraudulent Transaction

## Notes

- Features V1 to V28 are anonymized using PCA.
- Only the Time and Amount columns retain their original meaning.
- The dataset is highly imbalanced, with fraudulent transactions accounting for less than 1% of all records.