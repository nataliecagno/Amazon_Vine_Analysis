# Amazon_Vine_Analysis

## Project Overview
For this analysis, we are reviewing the product reviews for the Amazon Vine Program. OF the available products to investigate, I have chosen to look into the data for the Wireless products. Using Pyspark and AWS RDS to perform the ETL process, the end results will determine if there is a favorable review bias from the Amazon Vine Members of the dataset.

## Results
### How many Vine reviews and non-Vine reviews were there?
There we 65,581 reviews for the wireless products. Of the nearly 66k reviews, only 613 were vine reviews, and 64,968 were non-Vine reviews.

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
In the data set, there were 30,765 5-star reviews. 222 were vine reviews and 30543 were non-vine reviews.

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
Of the total dataset, 46.9% were five-stars.
Taking a closer look into the vine vs non-vine reviews, 47.6% of Vine reviews were 5-stars and 45.7% of the non-Vine reviews were 5-star reviews.

## Summary
To conclude, there is little evidence of a positive bias for Vine-members. The percentages of 5 star reviews only differ by less than 2%. It should be noted that while the Vine-reviews % is slightly higher, there sizes of the data set are extremely different. With nearly 66,000 reviews, there were barely 600 from Vine members. So while it is impressive that nearly 50% of the Vine reviews were 5 stars, it is notably more impressive that about 45% of the non-Vine reviews were also 5-stars.
