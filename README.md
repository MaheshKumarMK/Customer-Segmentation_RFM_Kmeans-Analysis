# Customer-Segmentation_RFM_Kmeans-Analysis
 Finding the useful insights about the customer purchasing history that can be an added advantage for the online retailer and Segment the customers based on their purchasing behavior.
About Data
This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

For a better understanding and more information, please refer to https://archive.ics.uci.edu/ml/datasets/Online+Retail

The features in the given dataset are:
InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
Description: Product (item) name. Nominal.
Quantity: The quantities of each product (item) per transaction. Numeric.
InvoiceDate: Invoice Date and time. Numeric, the day and time when each transaction was generated.
UnitPrice: Unit price. Numeric, Product price per unit in sterling.
CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
Country: Country name. Nominal, the name of the country where each customer resides.
Problem statement
Using the above data, find useful insights about the customer purchasing history that can be an added advantage for the online retailer.
Segment the customers based on their purchasing behavior.
Solution Proposed
First of all, to observe the structure of the data and missing values, you can use exploratory data analysis and data visualization techniques.

You must do descriptive analysis. Because you must understand the relationship of the features to each other and clear the noise and missing values in the data.

Analyse the distribution of Orders, Customers and Countries. These analyzes will help the company develop its sales policies and contribute to the correct use of resources. After that, the data set will be ready for RFM analysis.

RFM analysis is a data-driven customer behavior segmentation technique where RFM stands for recency, frequency, and monetary value.

The idea is to segment customers based on when their last purchase was(Recency), how often they’ve purchased in the past(Frequency), and how much they spent(Monetary). All three of these measures have proven to be effective predictors of a customer’s willingness to engage in marketing messages and offers.

Segment the customers based on past purchasing behavior by RFM analysis.

By using RFM Analysis, you can enable companies to develop different approaches to different customer segments so that they can get to know their customers better, observe trends better, and increase customer retention and sales revenues.

Calculate the Recency, Frequency and Monetary values of the customers in the RFM Analysis using the data.

In the Customer Segmentation section, create an RFM Segmentation Table where you segment your customers by using the RFM table. For example, you can label the best customer as "Big Spenders" and the lost customer as "Lost Customer".

We will segment the customers ourselves based on their recency, frequency, and monetary values. But can an unsupervised learning model do this better for us? You will use the K-Means algorithm to find the answer to this question. Then you will compare the classification made by the algorithm with the classification you have made yourself.

Descriptive analytics: What happened?
Diagnostic analytics: Why did it happen?
Predictive analytics: What is likely to happen in the future?
Prescriptive analytics: What is the best course of action to take?
