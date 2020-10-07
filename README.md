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


### Vine reviews 
- 

- Vine reviews (Vine_reviews.ipynb) google colab link:

https://colab.research.google.com/drive/1fYhQa-IVwQNvjp1nyNCoGXavR4RJtE1w?usp=sharing