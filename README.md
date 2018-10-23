# Credit-Card-Fraud-Detection

The Credit Card Fraud Detection Problem includes modeling past credit card transactions with the knowledge of the ones that turned out to be fraud. This model is then used to identify whether a new transaction is fraudulent or not. Our aim here is to detect 100% of the fraudulent transactions while minimizing the incorrect fraud classifications.

### Data Set Analysis:

This problem has been picked from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud).

### Observations

The data set is highly skewed, consisting of 492 frauds in a total of 284,807 observations. This resulted in only 0.172% fraud cases. This skewed set is justified by the low number of fraudulent transactions.
The dataset consists of numerical values from the 28 ‘Principal Component Analysis (PCA)’ transformed features, namely V1 to V28. Furthermore, there is no metadata about the original features provided, so pre-analysis or feature study could not be done.
The ‘Time’ and ‘Amount’ features are not transformed data.
There is no missing value in the dataset.

## Theory

Credit Card Fraud Detection is a typical example of classification. In this process, we have focused more on analyzing the feature modeling and possible business use cases of the algorithm’s output than on the algorithm itself. We used the implementation of Local Outlier Factor (LOF) and Isolation Forest Algorithm to identify transactions with a high probability of being credit card fraud.




## Results

![Histogram](https://raw.githubusercontent.com/rahuls321/Credit-Card-Fraud-Detection/master/output_10_0.png)

![Confusion Matrix](https://raw.githubusercontent.com/rahuls321/Credit-Card-Fraud-Detection/master/output_12_0.png)


[Source](https://www.3pillarglobal.com/insights/credit-card-fraud-detection)
