# Amazon_Vine_Analysis
## Overview of the project
The purpose of this project is to analyze Amazon reviews on camera products written by members of the paid Amazon Vine program. The project consists of two tasks:
* Use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. 
* Use PySpark to determine if there is any bias toward favorable reviews from Vine members.

## Results
#### I. How many Vine reviews and non-Vine reviews were there? 
![5a](Resources/5a.png)
![5d](Resources/5d.png)
* There are 607 Vine reviews and 50522 non-Vine reviews.
#### II. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars? 
![5b](Resources/5b.png)
![5e](Resources/5e.png)
* 257 Vine reviews and 25220 non-Vine reviews were 5 star. 
#### III. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
![5c](Resources/5c.png)
![5f](Resources/5f.png)
* 42.3% Vine reviews and 49.9% non-Vine reviews were 5 stars.

## Summary
There are 42.3% of 5 star Vine reviews comparing to 49.9% of 5 star non-Vine reviews, which suggests there is no bias toward favorable reviews from Vine members. In order to support this statement, we can conduct a further analysis on 5 star reviews among verified purchase to determine if there is any bias toward favorable reviews from paid Vine members, as verified purchase reviews are much more genuine and trusted. 