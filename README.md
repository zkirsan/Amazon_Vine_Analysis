# Amazon_Vine_Analysis

## Overview of the analysis: 

There are approximately 50 datasets accessible in this project. Each one contains product reviews ranging from clothing to wireless devices. The goal of this project is to select one of these datasets and use PySpark to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, use PySpark, Pandas, or SQL to see if there is any bias toward positive Vine member reviews in your dataset. The analysis will then be summarised for Jennifer to submit to the SellBy stakeholders.

## Results: 

The findings provide answers to the following questions:
  - How many Vine reviews and non-Vine reviews were there?
  - How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

### Vine Reviews

<p align="center"><img src="https://github.com/zkirsan/Amazon_Vine_Analysis/blob/main/Resources/Vine_Program_Paid.PNG"></img></p>

### non- Vine Reviews

<p align="center"><img src="https://github.com/zkirsan/Amazon_Vine_Analysis/blob/main/Resources/Vine_Program_UnPaid.PNG"></img></p>


## Summary: 

As a result, when looking at non-Vine and Vine reviews, it illustrates that the percentage of both with 5-stars is the same, which is 46.99%. Furthermore, when I look at the percentage of paid reviews based on total data, I see that it is 0.68%. That gives us a real sample of paid data in the total data, which means the sample determines the bias in this dataset. 

<p align="center"><img src="https://github.com/zkirsan/Amazon_Vine_Analysis/blob/main/Resources/additional_analysis.PNG"></img></p>


