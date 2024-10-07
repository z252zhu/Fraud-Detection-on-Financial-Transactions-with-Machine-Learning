# Fraud Detection on Financial Transactions with Machine Learning

## Dataset Information

The dataset is derived from public dataset on Kaggle ([link](https://www.kaggle.com/datasets/chitwanmanchanda/fraudulent-transactions-data/data)). The data for the case is in CSV format with 6362620 rows and 10 columns originally.

- **step** - a unit of time in the real world. In this case 1 step is 1 hour of time.

- **type** - type of transaction: CASH-IN, CASH-OUT, DEBIT, PAYMENT and TRANSFER.

- **amount** - amount of the transaction.

- **nameOrig** - initiator of the transaction

- **oldbalanceOrg** - balance before the transaction

- **newbalanceOrig** - balance after the transaction

- **nameDest** - recipient of the transaction

- **oldbalanceDest** - initial balance of recipient before the transaction.

- **newbalanceDest** - new balance of recipient after the transaction

- **isFraud** - the transactions made by the fraudulent agents inside the simulation.

- **isFlaggedFraud** - the transacton that is flagged for illegal attempts which invole more than 200,000 in a single transaction.

Feature engineering and machine learning techniques are applied to detect fraudulent activities in the analysis.
