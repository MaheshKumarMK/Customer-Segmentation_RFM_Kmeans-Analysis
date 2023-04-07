## About Data

- This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

- For a better understanding and more information, please refer to https://archive.ics.uci.edu/ml/datasets/Online+Retail

## The features in the given dataset are:

- InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
- StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
- Description: Product (item) name. Nominal.
- Quantity: The quantities of each product (item) per transaction. Numeric.
- InvoiceDate: Invoice Date and time. Numeric, the day and time when each transaction was generated.
- UnitPrice: Unit price. Numeric, Product price per unit in sterling.
- CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
- Country: Country name. Nominal, the name of the country where each customer resides.

## Problem statement
1. Using the above data, find useful insights about the customer purchasing history that can be an added advantage for the online retailer.
2. Segment the customers based on their purchasing behavior.

## Solution Proposed

1. First of all, to observe the structure of the data and missing values, you can use exploratory data analysis and data visualization techniques.


2. You must do descriptive analysis. Because you must understand the relationship of the features to each other and clear the noise and missing values in the data.


3. Analyse the distribution of Orders, Customers and Countries. These analyzes will help the company develop its sales policies and contribute to the correct use of resources. After that, the data set will be ready for RFM analysis.


   - RFM analysis is a data-driven customer behavior segmentation technique where RFM stands for recency, frequency, and monetary value.

   - The idea is to segment customers based on when their last purchase was(Recency), how often they’ve purchased in the past(Frequency), and how much they spent(Monetary). All three of these measures have proven to be effective predictors of a customer’s willingness to engage in marketing messages and offers.


4. Segment the customers based on past purchasing behavior by RFM analysis.


5. By using RFM Analysis, you can enable companies to develop different approaches to different customer segments so that they can get to know their customers better, observe trends better, and increase customer retention and sales revenues.


6. Calculate the Recency, Frequency and Monetary values of the customers in the RFM Analysis using the data.


7. In the Customer Segmentation section, create an RFM Segmentation Table where you segment your customers by using the RFM table. For example, you can label the best customer as "Big Spenders" and the lost customer as "Lost Customer".


8. We will segment the customers ourselves based on their recency, frequency, and monetary values. But can an unsupervised learning model do this better for us? You will use the K-Means algorithm to find the answer to this question. Then you will compare the classification made by the algorithm with the classification you have made yourself.


- Descriptive analytics: What happened?
- Diagnostic analytics: Why did it happen?
- Predictive analytics: What is likely to happen in the future?
- Prescriptive analytics: What is the best course of action to take?

## Conclusion
- Cluster 0 : The first cluster is more related to the "Loyalists" or "Recent Customers." 


  **Create targeted marketing campaigns:** Use the information about these potential loyalists to create targeted marketing campaigns that speak to their interests and needs. This can include personalized offers, discounts, and promotions that are designed to encourage them to make additional purchases.

  **Improve your customer service:** Make sure that you are providing excellent customer service to all of your customers, including the ones with low monetary value and low frequency but high recency. Respond quickly and efficiently to their inquiries, address any issues they may have, and make sure that they feel valued and appreciated.

  **Offer loyalty programs:** Consider creating a loyalty program that rewards customers for making repeat purchases. This can help to encourage these potential loyalists to become more frequent customers and increase their monetary value over time.

  **Collect feedback:** Collect feedback from these customers to better understand their needs and preferences. Use this information to improve your products or services and create a better customer experience.

  **Engage with them on social media:** Engage with these customers on social media platforms like Facebook, Instagram, and Twitter. This can help to build a relationship with them, and make them feel more connected to your brand. You can also use social media to share content that is relevant to their interests and needs.
  
  
  
  - Cluster 1 : The second cluster belongs to the Loyal and "Top/Best Customers" but Churning" customers. 

  **Re-engage with personalized outreach**: The business can reach out to these customers with personalized communication, such as an email or phone call, to understand why they have not made a purchase recently. By listening to their feedback, the business can address their concerns and provide solutions to win back their loyalty.

  **Offer targeted promotions:** The business can offer targeted promotions or discounts to incentivize these customers to make a purchase. By understanding their past purchase behavior, the business can create customized offers that align with their interests and preferences.

  **Improve the customer experience:** The business can improve the customer experience by addressing any issues that may have caused the customer to churn. By creating a seamless and positive experience, the business can encourage these customers to return and continue their loyalty.

  **Implement a loyalty program:** A loyalty program can incentivize customers to continue their engagement with the business by offering rewards or exclusive benefits. By rewarding these customers for their loyalty, the business can encourage them to continue making purchases.

  **Monitor customer behavior:** The business can monitor the behavior of these customers to understand any changes in their engagement. By tracking their activity, the business can identify any signs of churn and take proactive measures to prevent it.
