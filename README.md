# Amazon_Vine_Analysis
Enter the world of Big data as we perform ETL on dataset from Amazon.

# Overview of the analysis: 
 one of amazon office products reviews dataset needs more Analysis so I used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then i used PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in my dataset.

# Results:
The total paid and unpaid office products rerviews are 2,642,215  , from this 49% are vine and 60% are non-vine.

#  total paid number of reviews
29188

# paid 5-star reviews
14333

# paid 5-star reviews percentage
49%

# unpaid total number of reviews
2613215

# unpaid 5-star reviews
1569844

# unpaid 5-star reviews percentage
60%

![Amazond](https://user-images.githubusercontent.com/77947860/184723512-c6794d9c-9d39-4ff0-80a8-440100a869d1.png)

![image](https://user-images.githubusercontent.com/77947860/184723835-fb2b3b31-0c7c-4041-976d-96469df32935.png)

# summary
49% of the reviews in the paid program were 5 stars reviews whereas the percentage in the unpaid reviews is  60%. This describes a positivity bias for reviews in the unpaid programs.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.
