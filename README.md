# Durable_Goods_Customer_Analysis

This project identifies and diffrentiaties the customer segment for a Durable goods store using RFM technique. It also calculates the Customer Lifetime Value for different segments.

## Objective
To identify our best and valuable customers and develop marketing strategies to retain them and invest in the right customer category to increase company profits.<br>
Our approach:
* Customer segmentation 
* Customer Lifetime value
* Targeting customers

## Dataset
We have a panel dataset containing transactional records of 19,936 households during six years period.

## Methodology
* Data Cleaning & aggregation
* RFM Analysis
* Clustering & evaluvation
* Calculate CLV(Customer Lifetime Value)
* LDA evaluation (Linear Discriminant Analysis)

## RFM clustering results
> There are mainly three segments from the RFM analysis. 
> 1. Premium Customer
> 2. Valuable Customer
> 3. New Customer
![figure](https://github.com/nikhilarosekuruvilla/Durable_Goods_Customer_Analysis/blob/master/Images/Clustering_results.png)

## CLV of Segments
> As expected, the CLV value for Premium customer is the highest followed by Valuable and New customer.We could also identify a segment which uses online shopping more than others(from LDA analysis.)
![figure](https://github.com/nikhilarosekuruvilla/Durable_Goods_Customer_Analysis/blob/master/Images/CLV_segments_1.png)

## Recommendations
![figure](https://github.com/nikhilarosekuruvilla/Durable_Goods_Customer_Analysis/blob/master/Images/Managerial_insights.png)

## Data challenges
* There are households which have return transactions without any purchase record for some items. 
* Transaction types for returns are categorized as transaction type 2 or 4, however returns can occur in any transaction type.
* Missing values 

