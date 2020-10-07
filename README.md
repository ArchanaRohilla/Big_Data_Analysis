# Big Data Analysis
Amazon vine reviews analysis using PySpark and AWS

## Project Overview
In this project, a complete ETL process has been performed in the AWS cloud platform and uploaded DataFrame to an AWS RDS instance. 
PySpark has been used to perform a statistical analysis of reviews of electronics items sold on Amazon.

## Tools
PySpark, AWS RDS/S3, Google Colab Notebook, pgAdmin, SQL

## Summary

### Amazon reviews- ETL
- Extracted the "Electronics Items" reviews dataset from the list of review datasets from AWS S3 bucket and loaded into a DataFrame.

- Conducted necessary Transformations of the extracted dataset to make sure that the DataFrames match in both data type and column name. 
This will fit the dataset into tables of the schema file.

- Loaded the DataFrames that correspond to tables into an AWS RDS instance.

- Amazon reviews ETL (Amazon_reviews_ETL.ipynb) google colab link:

https://colab.research.google.com/drive/17o2j3lKEkRBbhWDNateZBZn0WYc-v2qt?usp=sharing


### Vine reviews analysis
- Many of Amazon's shoppers depend on product reviews to make a purchase.

- There were total 3093660 reviews in the cleaned electronics dataset.

- Out of the total 3093660 reviews, 18512 were the reviews which belong to vine-program whereas 3075148 reviews do not belong to the vine-program.

- The average star rating of the vine(paid) reviews is 4.135 whereas the average star rating of the non-vine(unpaid) reviews is 4.035.

- The "5-star-rating" and "4-star-rating" of the vine reviews are more as compared to the other ratings(1,2,3).

- The "5-star-rating" and "4-star-rating" of the non-vine reviews are also more as compared to the other ratings(1,2,3).

- The number of helpful votes are more in case of non-vines reviews.

- There is negligiable difference between the average ratings of vine and non-vine reviews. Hence, it can be concluded that the vine reviews are not biased and can be trusted.

- Vine reviews (Vine_reviews.ipynb) google colab link:

https://colab.research.google.com/drive/1fYhQa-IVwQNvjp1nyNCoGXavR4RJtE1w?usp=sharing