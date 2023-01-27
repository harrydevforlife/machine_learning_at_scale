# Big Data Application: Machine Learing at Scale

## Motivation

As an enthusiast of recommender systems and food lovers in general, we've always been curious about 2 things:  
- What makes some restaurants famous ? Is there a way to quantify and even recommend those restaurants to others ?
- How does the recommendation algorithm work? In this project, we will expand on what attributes determine the popularity of restaurants and how can this affect the accuracy of recommendation systems ?  

Then we realized the Yelp dataset, which is a collection of Yelp businesses, reviews, and user data. It was originally brought together for Yelp's Challenges dataset, which is an opportunity for students to conduct research or analyze Yelp data and share their discoveries. The most recent dataset, includes information on businesses across 8 metropolitan areas in the United States and Canada.  

Given a large number of Yelp business reviews, we wanted to be able to handle large amounts of data. Therefore, we decided to use this as an opportunity to learn and use Apache Spark, as well as apply model optimization methods to big data. This project will be implemented on Databricks and uses the Alternating Least Squares suggestive model.

## Testing model  

Root Mean Squares Error.  
RMSE = 1.47

Recommend 4 restaurants for 5 users:

    +------+----------+---------+  
    |userid|businessid|   rating|  
    +------+----------+---------+  
    |    20|     26777|5.2499027|  
    |    20|     59308| 4.724409|  
    |    20|     13385|  4.68757|  
    |    20|     41707|4.6628594|  
    |    15|     26777|5.0053034|
    |    15|     26624| 4.466009|
    |    15|     41707|4.3750315|
    |    15|     13385|4.3227687|
    |     9|     26777|5.9033422|
    |     9|     59308| 5.204884|
    |     9|     13385| 5.177756|
    |     9|     67016|5.1294346|
    |    25|     26777| 5.075195|
    |    25|     13385|4.5821505|
    |    25|     59308| 4.581125|
    |    25|     51996| 4.559071|
    |    30|     26777| 5.650303|
    |    30|     13385| 5.038804|
    |    30|     59308|5.0381665|
    |    30|     56871| 4.978765|
    +------+----------+---------+