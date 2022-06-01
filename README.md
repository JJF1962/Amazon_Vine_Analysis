# Amazon_Vine_Analysis
## Overview of the Analysis
For this project we partnered with Jennifer, an account manager at BigMarket. SellBy, our client, loves to talk about the power of big data, but Jennifer isn't a data expert. So we started off the project by giving her a quick overview of what big data actuallyas indicated below:Jennifer during the module 16, it was learned what constitutes big data and how it's handled. it was covered Hadoop and its ecosystem. MapReduce and how it has improved the process for handling big data. and also PySpark, which has become the leading technology for handling big data.
As a amin editor was used for the schema file PG Adming and for the coding of the two deliverables Google Colab, very similar to Jupyter Notebook, but with big storage capacity as works with Google servers.
After diving into some of the technologies used with big data, It was used and studied  at natural language processing (NLP) in relation to big data. with an introduction to cloud services. Cloud services allow store large amounts of data at remote locations rather than locally, on top of many other services. This allows for more scalability and performance. and it was used extensively the most popular cloud service available: Amazon Web Services (AWS). All of this will help us to develop well this challenge with the following deliverables:

* Deliverable 1: Perform ETL on Amazon Product Reviews
* Deliverable 2: Determine Bias of Vine Reviews
* Deliverable 3: A Written Report on the Analysis README.md

## Results
## Deliverable # 1 Perform ETL on Amazon Product Reviews
It was used the  cloud ETL process, to create an AWS RDS database with tables in pgAdmin, selected a dataset from the Amazon Review datasets for the website shown below
https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_v1_00.tsv.g

Later using codes it was extracted the dataset into a DataFrame. and posteriorly transformed  the DataFrame into four different DataFrames, matching the echema in pgAdmin. finally it was uploaded the transformed data into four tables and ran the queries in pgAdmin to confirm that the data has been uploaded. To see the outcome in pg Admin it was used a simple code in the editor select * table_name as shown in the figures below:

customers_table

![this is an image](https://github.com/JJF1962/Amazon_Vine_Analysis/blob/main/Images/Capture%20customers_table.PNG)

products_table

![this is an image](https://github.com/JJF1962/Amazon_Vine_Analysis/blob/main/Images/Capture%20products_table.PNG)

rewiew_id_table

![this is an image](https://github.com/JJF1962/Amazon_Vine_Analysis/blob/main/Images/Capture%20review_id_table.PNG)

vine_table

![this is an image](https://github.com/JJF1962/Amazon_Vine_Analysis/blob/main/Images/Capture.vine_table.PNG)


## Deliverable 2 Determine Bias of Vine Reviews
It was usedg either PySpark to complete Deliverable 2.
It was Filtered the data and created a new DataFrame or table to retrieve all the rows where the total_votes count is equal to or greater than 20 to pick reviews that are more likely to be helpful and to avoid having division by zero errors later on. Filter the new DataFrame or table created in Step 1 and create a new DataFrame or table to retrieve all the rows where the number of helpful_votes divided by total_votes is equal to or greater than 50%.as you cansee in the attached Vine_Review_Analysis.ipynb


## Summary
The tools amd metodology learned was very powerful and allow to manage and analize properly big data, imposible to manange ina local server
