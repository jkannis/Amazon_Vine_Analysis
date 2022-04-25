# Amazon_Vine_Analysis
Pyspark

## Overview
The purpose of this project is to filter Amazon reviews data and analyze whether the paid Vine program creates bias. 
The dataset used for this analysis: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Outdoors_v1_00.tsv.gz

## Results
- There were 107 Vine reviews and 39,869 non-Vine reviews in this dataset.
- There were 56 Vine 5-star reviews and 21,005 non-Vine 5-star reviews.
- 52% of the Vine reviews were 5-star reviews. 53% of the non-Vine reviews were 5-star reviews.
![Vine Reviews](https://github.com/jkannis/Amazon_Vine_Analysis/blob/main/Resources/Paid_Reviews_Results.png)

![Non-Vine Reviews](https://github.com/jkannis/Amazon_Vine_Analysis/blob/main/Resources/Unpaid_Reviews_Results.png)

## Summary
Based on the results using the Outdoors dataset from Amazon, there does not appear to be any bias for reviews in the Vine program. The percentage of 5-star reviews is virtually the same for both the paid and unpaid reviews.
### Additional Analysis Recommendations
1. It might be interesting to consider the price of the items being reviewed when doing this analysis. Is it possible that the paid reviews tend to be for higher-priced items, which would benefit Amazon?
2. It might also be beneficial to consider other levels of ratings when comparing both groups.
