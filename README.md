# market-segmentation-of-credit-card-customers
This case requires us to develop customer segmentation to define marketing strategies. An exhaustive analysis using Clustering techniques, namely K-means and DBSCAN was carried out.

### Dataset
Credit card dataset on Kaggle: https://www.kaggle.com/arjunbhasin2013/ccdata
The dataset summarizes the usage behavior of about 9000 active credit card holders in a 6 months period. The file is at a customer level with 18 behavioral variables.

### Data dictionary
1.  CUST_ID : Identification of Credit Card holder (Categorical)
2.  BALANCE : Balance amount left in their account to make purchases (
3.  BALANCE_FREQUENCY : How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)
4.  PURCHASES : Amount of purchases made from account
5.  ONEOFF_PURCHASES : Maximum purchase amount done in one-go
6.  INSTALLMENTS_PURCHASES : Amount of purchase done in installment
7.  CASH_ADVANCE : Cash in advance given by the user
8.  PURCHASES_FREQUENCY : How frequently the Purchases are being made, score between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)
9.  ONEOFFPURCHASESFREQUENCY : How frequently Purchases are happening in one-go (1 = frequently purchased, 0 = not frequently purchased)
10. PURCHASESINSTALLMENTSFREQUENCY : How frequently purchases in installments are being done (1 = frequently done, 0 = not frequently done)
11. CASHADVANCEFREQUENCY : How frequently the cash in advance being paid
12. CASHADVANCETRX : Number of Transactions made with "Cash in Advanced"
13. PURCHASES_TRX : Numbe of purchase transactions made
14. CREDIT_LIMIT : Limit of Credit Card for user
15. PAYMENTS : Amount of Payment done by user
16. MINIMUM_PAYMENTS : Minimum amount of payments made by user
17. PRCFULLPAYMENT : Percent of full payment paid by user
18. TENURE : Tenure of credit card service for user
 
### Prerequisites
Libraries that need to be installed are: numpy, pandas, matplotlib, seaborn, sklearn.

### Installing
Libraries can be installed using pip command.
```
pip install pandas
```
