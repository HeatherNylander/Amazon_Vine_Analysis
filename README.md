# Amazon_Vine_Analysis

## Overview
Since your work with Jennifer on the SellBy project was so successful, you’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

## Results
#### How many Vine reviews and non-Vine reviews were there?
![image](https://user-images.githubusercontent.com/92553327/162681372-c89baaa8-db28-4b44-9cb1-6cca072da199.png)
- Vine: 4291 
- Non-Vine: 40565

#### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
![image](https://user-images.githubusercontent.com/92553327/162681182-7b275007-b5df-40c7-9b24-84805896a6ec.png)
- 15711 5 star reviews
- 15663 non vine 5 star reviews

#### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
![image](https://user-images.githubusercontent.com/92553327/162681091-1e620148-9729-4825-8baa-c08dad4db962.png)
- 38.8 %


## Summary
- The Vine program does not appear to show any bias.
