# Olist Customer Reviews Analysis

## Introduction
Olist is the biggest online platform that connects sellers and customers from all over Brazil without hassle and with a single contract. Those merchants can sell their products through the Olist Store and ship them directly to the customers using Olist logistic partners. In this analysis, I use a popular public dataset that can be easily accessed on the internet "olist.db". 

## Analysis
There are 6 analyses carried out here.
1. Overall customer reviews score distribution
2. Comment message keywords
3. Product categories reviews
4. Delivery times and review scores distribution
5. Delivery times correlation analysis
6. Seller and customer locations distribution

Mainly using pandas library to create DataFrame for analysis and SQLite3 to access data needed from the database.
For analysis some of the libraries used for this analysis;
<img src="https://github.com/dzakiyma/olist_analysis_reviews/assets/137891087/a3dd149a-0971-4a83-90ff-24532d8ac58e">

### 1. Customer reviews score distribution
This analysis carried out on the review scores from the customers and has the objective to see what is the level of satisfaction of customers who use this product as a whole.

### 2. Comment message keywords
After we know the distribution of review scores given by customers, this analysis wants to know deeper what keywords or aspects that customers include along with giving a review. Further, we know that 'product' and 'delivery time' (includes time, delay, waiting, and receive) are some of the aspects customers often deliver when giving bad reviews.

### 3. Product categories reviews
From the product aspect, we can get information that the security and services product category has the lowest review score from customers. Since then, Olist can be considering or evaluating this product category more deeply either setting standards regarding product quality, etc.

### 4. Delivery times and review scores distribution
From the delivery times aspect, this analysis tells us that there are negative correlation between delivery times and review scores given by customers. Customers who get orders with longer delivery times tend to give bad reviews.

### 5. Delivery times correlation analysis
So, we need to know why an order gets a long delivery time. Basically, in my opinion, the delivery time is associated with the distance and dimension or weight of the product. This analysis was carried out to check the correlation of those factors to delivery time. 

### 6. Seller and customer location distribution
Based on previous analysis we know that distance has a positive correlation with delivery times. The distance referred to in this case is about how far the distance between the seller and the customers is in order.
