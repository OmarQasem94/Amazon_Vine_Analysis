# Amazon_Vine_Analysis


## **Overview**

In this project a dataset that includes data on Amazon reviews left by users that purchased video games was used to analyze whether there is a bias towards positive reviews from Vine members. The Amazon Vine program was coupled with a reward program for members that leave a review. The analysis utilizes PySpark to extract, transform, and load (ETL) the data to an AWS RDS. The RDS was connected to PostgreSQL and the data was loaded to PgAdmin to facilitate simple access and manipulation of the data.


## **Results**

#### Total Number of Reviews

* Vine Reviews

![vine_reviews](https://github.com/OmarQasem94/Amazon_Vine_Analysis/blob/main/images/vine_reviews.PNG)


* Non-Vine Reviews

![no_vine_reviews](https://github.com/OmarQasem94/Amazon_Vine_Analysis/blob/main/images/no_vine_reviews.PNG)


#### Total Number of Five-Star Reviews

* Vine Reviews

![Vine_five_star](https://github.com/OmarQasem94/Amazon_Vine_Analysis/blob/main/images/Vine_five_star.PNG)


* Non-Vine Reviews

![No_Vine_five_star](https://github.com/OmarQasem94/Amazon_Vine_Analysis/blob/main/images/No_Vine_five_star.PNG)


#### Percentage of Five-Star Reviews

* Vine Reviews

![percentage_five-star_reviews](https://github.com/OmarQasem94/Amazon_Vine_Analysis/blob/main/images/percentage_five-star_reviews.PNG)


* Non-Vine Reviews

![percentage_non_five-star_reviews](https://github.com/OmarQasem94/Amazon_Vine_Analysis/blob/main/images/percentage_non_five-star_reviews.PNG)


## **Summary**

The analyses shows that 51% of the reviews in the vine program were 5 star reviews whereas the precentage of five-star reviews for non-vine reviews was 39%. This depicts that the reviews for the vine-program are positively biased due to the rewards program.

Due to the huge disparity between the number of reviews for Amazon members and Amazon Vine members the distribution of a sample could be very biased and hence not normally distributed. A non-parametric test would be more suitable to test a dataset with these characteristics.