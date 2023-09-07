# Olist Customer Reviews Analysis

## Introduction
Olist is the bisggest oline platform that connects sellers and customers from all over Brazil without the hassle and with a single contract. Those merchants are able to sell their products through the Olist Store and ship them directly to the customers using Olist logistic partners. In this analysis I use public dataset which is popular and can be easily accessed on the internet "olist.db". 

## Analysis
There are 6 analyses carried out here.
1. Overall customer reviews score distribution
2. Comment message keywords
3. Product categories reviews
4. Delivery times and review scores distribution
5. Delivery times correlation analysis
6. Seller and customer locations distribution
Mainly using pandas library to creating DataFrame for analysis and sqlite3 to access data needed from database.
For analysis some of libraries used for this analysis;
<img src="https://github.com/dzakiyma/olist_analysis_reviews/assets/137891087/a3dd149a-0971-4a83-90ff-24532d8ac58e">

### 1. Customer reviews score distribution
This analysis carried out on the reviews score from the customers and have the objective to see what is the level of satisfaction of customers who use this product as a whole.

### 2. Comment message keywords
After we know the distribution of reviews score given by customers, this analysis want to know deeper what keywords or aspects that customers includes along with giving a review. Further we know that 'product' and 'delivery time' (includes time, delay, waiting, receive) are some of aspects customer often delivered when giving a bad reviews.

### 3. Product categories reviews
From product aspect we can get information that security and services producut category has the lowest review score from customers. Since that, olist can considering or evaluating this product category more deeper either setting standards regarding product quality or etc.

### 4. Delivery times and review scores distribution
From delivery times aspect, this analysis tells us that there are negative correlation betwwen delivery times and rewiew score given by customers. Customers who get orders with longer delivery times tends to give a bad reviews.

### 5. Delivery times correlation analysis
So, we need know why an order gets a long delivery time. Basically, from my opinion the delivery time associated with distance and dimension or weight of the product. This analysis carried out to check correlation those factors to delivery time. 

### 6. Seller and customer locations distribution
Based on previous analysis we know that distance has a positive correlation with delivery times. The distance reffered to in this case is about how far distance between seller and customers in an order.
