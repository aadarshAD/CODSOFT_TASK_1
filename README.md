# CODSOFT_TASK_1


Task 1: "CREDITCARD FRAUD DETECTION" 💳

image

Credit card fraud detection is a type of fraud detection that uses machine learning to identify fraudulent credit card transactions. The goal of credit card fraud detection is to prevent fraudulent transactions from being approved, while minimizing the number of legitimate transactions that are incorrectly flagged as fraudulent.

ABOUT DATASETS: URL : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

This datasets have 492 frauds out of 284,807 transactions. It is highly unbalanced, the positive class--1 (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Due to confidentiality issues, the original features are not provided and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'.

Feature Time contains the seconds elapsed between each transaction and the first transaction in the dataset.But, we did not consider Time for training purpose as it is of no use to build the models and may not impact our target variable.

The feature Amount is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning.

Feature Class is the response variable and it takes value 1 in case of fraud and 0 otherwise.

STEPS :

Importing Libraries & Loading Datasets.

Data Preprocessing & Preparing Datasets.

Exploratoty Data Analysis(EDA) & Visualization.

Handling Imbalanced Datasets.

Conclusions.

CONCLUSION:- In conclusion, our credit card fraud detection project has successfully developed a robust system capable of identifying fraudulent transactions with a high degree of accuracy. This achievement has the potential to significantly reduce financial losses and enhance customer trust. While our current model demonstrates impressive results, the ever-evolving nature of fraud necessitates ongoing efforts to refine and improve our detection methods.
