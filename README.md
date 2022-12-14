# Amazon_Vine_Analysis

## Overview

The purpose of this project is to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. The following tasks are to be completed: 

1. Perform ETL on Amazon Product Reviews.
2. Determine Bias of Vine Reviews.
3. A Written Report on the Analysis.

## Results

***Deliverable 1: Perform ETL on Amazon Product Reviews***
Using knowledge of the cloud ETL process, create an AWS RDS database with tables in pgAdmin, pick a dataset from the Amazon Review datasets, and extract the dataset into a DataFrame. You'll transform the DataFrame into four separate DataFrames that match the table schema in pgAdmin. Then, upload the transformed data into the appropriate tables and run queries in pgAdmin to confirm that the data has been uploaded:

Figure 1:

![Image1](https://raw.githubusercontent.com/krismbah/Amazon_Vine_Analysis/main/D1.png)

Figure 1.1:

![Image1.1](https://raw.githubusercontent.com/krismbah/Amazon_Vine_Analysis/main/D1.1.png)

Figure 1.2:

![Image1.2](https://raw.githubusercontent.com/krismbah/Amazon_Vine_Analysis/main/D1.2.png)

Figure 1.3:

![Image1.3](https://raw.githubusercontent.com/krismbah/Amazon_Vine_Analysis/main/D1.3.png)

Figure 1.4:

![Image1.4](https://raw.githubusercontent.com/krismbah/Amazon_Vine_Analysis/main/D1.4.png)

Figure 1.5:

![Image1.5](https://raw.githubusercontent.com/krismbah/Amazon_Vine_Analysis/main/D1.5.png)


***Deliverable 2: Determine Bias of Vine Reviews***
Using knowledge of PySpark, Pandas, or SQL, determine if there is any bias towards reviews that were written as part of the Vine program. For this analysis, determine if having a paid Vine review makes a difference in the percentage of 5-star reviews:

Figure 2:

![Image2](https://raw.githubusercontent.com/krismbah/Amazon_Vine_Analysis/main/D2.png)

Figure 2.1:

![Image2.1](https://raw.githubusercontent.com/krismbah/Amazon_Vine_Analysis/main/D2.1.png)

Figure 2.2:

![Image2.2](https://raw.githubusercontent.com/krismbah/Amazon_Vine_Analysis/main/D2.2.png)

Figure 2.3:

![Image2.3](https://raw.githubusercontent.com/krismbah/Amazon_Vine_Analysis/main/D2.3.png)


## Summary

To summarize, this project gained access to approximately 50 datasets. Each one containing reviews of a specific product, from clothing apparel to wireless products. Choosing one of these datasets (electronics), PySpark was used to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, PySpark was also used to determine if there is any bias toward favorable reviews from Vine members in your dataset. The following summary is to be submitted to the SellBy stakeholders:

1. The paid dataset contained 1,080 reviews.
2. 454 of the 1,080 paid reviews were given 5-star ratings.
3. 42 percent of the paid reviews were given 5-star ratings.
4. The unpaid dataset contained 49,673 reviews.
5. 23,043 of the 49,673 unpaid reviews were given 5-star ratings.
6. There does not appear to be bias toward favorable reviews from Vine members who purchased electronic products on Amazon.
