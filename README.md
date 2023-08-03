# Customer Segmentation

### Welcome to the Customer Segmentation Project. 

Customer segmentation helps understand customers' needs, target marketing campaigns, optimize resources, enhance customer experience and build loyalty.

#### Business Objective: 
* By Analyzing the items frequently bought together, the store can create strategic product placement and promotions to increase average transaction value.
* Understanding different customer segments helps tailor products, services, and communication to meet individual segment requirements.
* Segmentation allows businesses to allocate resources efficiently by focusing on the most profitable customer segments and adjusting marketing efforts accordingly.

#### Tools used: Pandas, Numpy, Matplotlib, Sklearn

#### Data Understanding: 
* This data of Retail Transactions from 01 December 2010 to 09 December 2011
* Source Data: Online retail dataset by UCI Machine Learning Library.       
  https://archive.ics.uci.edu/ml/datasets/Online+Retail
* The dataset has 8 columns and 541909 rows.
* Data Dictionary:
    * InvoiceNo: Invoice number uniquely assigned to each transaction.
    * StockCode: Product (item) code.
    * Description: Product (item) name.
    * Quantity: The quantities of each product (item) per transaction.
    * InvoiceDate: The day and time when each transaction was generated.
    * UnitPrice: Product price per unit in sterling.
    * CustomerID: Customer number uniquely assigned to each customer.
    * Country: The name of the country where each customer resides.


#### Modeling Data
The k-Means clustering algorithm is an unsupervised machine learning algorithm that uses multiple iterations to segment the unlabeled data points into K different clusters in a way such that each data point belongs to only a single group that has similar properties.

K-means gives the best result under the following conditions:
* Data distribution is not skewed.
* Data is standardized.
* The data is highly skewed, therefore I will perform log transformations to reduce the skewness of each variable and I standardized the data.
* Finding the optimal number of clusters
![image](https://github.com/Nirali227/CustomerSegmentation/assets/76995087/15c87901-50cc-4e6c-8da7-57faf6e690ac)





