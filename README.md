# credit-card-fraud-detection
**Context:**  
Credit card companies must be able to detect fraudulent transactions to prevent customers from being charged for purchases they did not make.

**Content:**  
The dataset includes credit card transactions made by European cardholders. It covers a two-day period, with 473 cases of fraud out of 275,190 total transactions. Since only 0.172% of the transactions are fraudulent, the dataset is highly imbalanced.  

The data consists of numerical variables derived from a PCA (Principal Component Analysis) transformation. Due to confidentiality concerns, the original features and additional details about the dataset are not provided. The features are labeled V1, V2, ..., V28, representing the principal components generated through PCA. Two features, 'Time' and 'Amount,' were not transformed through PCA. The 'Time' feature represents the time in seconds since the first transaction, and the 'Amount' feature corresponds to the transaction value, which can be used for cost-sensitive learning. The target variable, 'Class,' indicates whether a transaction is fraudulent (1) or not (0).
