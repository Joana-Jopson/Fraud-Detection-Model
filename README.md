# Fraud Detection Model:

Fraudulent financial transactions can cause significant losses for financial institutions.
This project builds and compares supervised learning models to classify transactions as fraudulent or genuine, leveraging structured transaction data.

Key highlights:

-> Preprocessed and analyzed 6M+ transaction records.

-> Implemented Logistic Regression and Random Forest classifiers.

-> Achieved >90% detection accuracy on validation data.

-> Evaluated models using ROC-AUC, Precision-Recall, and Confusion Matrix.

-> Visualized fraud patterns and model results for actionable insights.

## 📂 Dataset

-> Source: Kaggle – Fraud Detection Dataset

-> Size: 6,362,620 rows × 10 columns

-> Key Fields:

  --> step → time unit (1 = 1 hour, 744 = 30 days)

  --> type → transaction type (CASH-IN, CASH-OUT, DEBIT, PAYMENT, TRANSFER)

  --> amount → transaction amount

  --> oldbalanceOrg, newbalanceOrig → sender’s balance before/after transaction

oldbalanceDest, newbalanceDest → recipient’s balance before/after transaction

isFraud → fraud label (1 = fraud, 0 = legitimate)
