# Amazon_Vine_Analysis

## Overview of the analysis: 
This analysis was done to test my abilities to work with large sets using Google collab, AWS and postgres.  The vehicle for this practice was the analysis of product reviews.  The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay a small fee to Amazon and provide products to Vine members, who are then required to publish a review.  We want to determine if there is a correlation between review results and vine membership.

Results: 

## How many Vine reviews and non-Vine reviews were there?
After filtering to sample of 1068, I identified 4 Vine reviews and 1064 none-Vine reviews.

## How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
Of the 4 vine reviews 1 was a 5-star and of 1064 none-Vine, 527 were 5 stars.

## What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
   For Vine reviews, 25% are 5 stars.  For none-Vine reviews are 49.5% are 5 stars.
   
   
![image](https://user-images.githubusercontent.com/99847046/180283975-157aa91a-7eea-42cf-bcf2-12dd79f28ebd.png)

![image](https://user-images.githubusercontent.com/99847046/180283996-9bf47c97-69da-449e-9194-71e2e8ccf706.png)

## Summary: 
There are significantly less Vine reviews than non-Vine reviews so it is difficult to rely on this information on its own.  However based on the data we cleaned there is no positive correlation with being a paid reveiwer and higher product rating. The percentage of 5-star ratings in fact fell for Vine members.  Another analysis that could be done is looking at verified purchases.  All 4 Vine reviews were not verified purchases.  Comparing the given ratings to persons who actually paid for the product could potentially highlight a true correlation.



