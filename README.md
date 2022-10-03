# Amazon_Vine_Analysis

## Overview

You’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

## Results

- How many Vine reviews and non-Vine reviews were there?

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

<p align="center">  
<img src="https://github.com/mcgibbenyd1/Amazon_Vine_Analysis/blob/main/Paid_Vine_Reviews.png" width="65%"/>
</p>
Dataframe of the total number of reviews with at least 20 votes with reviews made from the Paid Vine platform. Total Vine reviews, 5-Star Reviews and how many of those total reviews were 5 stars.

<p align="center">  
<img src="https://github.com/mcgibbenyd1/Amazon_Vine_Analysis/blob/main/Unpaid_Vine_Reviews.png" width="65%"/>
</p>
Dataframe of the total number of reviews from non-Vine accounts. Total Vine reviews, 5-Star Reviews and how many of those total reviews were 5 stars.

## Summary

In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

Based strictly on the percentage basis it can be said that there was a more favored positive review from the Paid Vine program with 51% providing 5 star reviews to the 38% on the non-Vine reviews giving 5 stars. 

One of the ways that could be helpful to invistigate the difference would be to further stratify by product category and see if there were specific subclasses that produced more negative reviews. 
