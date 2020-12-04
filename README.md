# CreditCardDefault
## Author: Xinman Zhang, Uriel Yang

This is the final project for CS 534 Machine Learning Course.

### Motivation
For banking and financial companies to succeed, it is important for them to assess the risk of losing money before lending to customers. More specifically, given the background information of a customer, a credit card issuing bank would like to predict if the client will have difficulty in making timely payments to his or her credit card installments. In this way, the company can make more prudent decisions on whether or not to sanction the loan to a client, and thus minimize the potential loss. 

### Goal
In this project, we will develop a model based on clients' information (personal backgrounds and past payment records). With the features provided in data, we hope our model will accurately predict loan defaults. Further, based on our predictions, we also expect to find the driving factors behind the loan defaults (i.e. the features which are strong indicators of a loan default). In this way, credit card issuing banks can utilize this knowledge for their risk assessments.

### Data Source
The dataset “Credit Card Fraud Detection” is collected from Kaggle competition. Here is the link to the dataset. https://www.kaggle.com/mishra5001/credit-card. There are three tables in the dataset, including application data, columns data, and previous application data. In this project, we will make use of  application data, with columns data as a supplementary to explain the meanings of different features.