# Unsupervised-Learning-Clustering
Dataset description : This dataset was derived and simplified for learning purposes. It includes usage behaviour of about 9000 active credit card holders during 6 months period. This case requires to develop a customer segmentation to define marketing strategy.

Columns explanation : 

CUST_ID: Identification of Credit Card holder (Categorical)
BALANCE_FREQUENCY: How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)
PURCHASES: Amount of purchases made from account 
CASH_ADVANCE: Cash in advance given by the user
CREDIT_LIMIT: Limit of Credit Card for user 
PAYMENTS: Amount of Payment done by user 

# Instructions

1. Import you data and perform basic data exploration phase
2. Perform the necessary data preparation steps ( Corrupted and missing values handling, data encoding, outliers handling ... )
3. Perform hierarchical clustering to identify the inherent groupings within your data. Then, plot the clusters. (use only 2 features. For example, try to cluster the customer base with respect to 'PURCHASES' and     'credit limit')
4. Perform partitional clustering using the K-means algorithm. Then, plot the clusters
5. Find the best k value and plot the clusters again.
6. Interpret the results
