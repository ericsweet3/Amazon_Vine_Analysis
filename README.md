# Amazon Vine Analysis

## Overview
- For this challenge I took a dataset that housed reviews on various video games, both paid and unpaid reviews. I analyzed the dataset to see if there is any bias towards how the paid members rate vs the un-paid members. 
- Tools Used:
  1) PySpark
  2) Postgres SQL
  3) Amazon RDS

## Results

1) How many Vine review and non-Vine reviews are there?
 - There are 94 vine reviews vs 40565 un-paid reviews

2) How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
 - Out of the 15711 5-star reviews, only 48 were paid

3) What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
 - .3% of the Vine reviews were 5-stars, which leaves 99.7% of the reviews to people that were un-paid.

Results shown here:

![vine review analysis](https://user-images.githubusercontent.com/75768098/115994064-183b8580-a59b-11eb-8312-baaad1ef9815.png)



## Summary
- As we can see from the percentages above, there is no evidence for a positive bias since the percentage of vine reviews that were 5 stars were lower than the non-vine. The next analysis that I would try to find is the average review percentage for the entire program, not just the 5-stars. The reason for this is that I believe even though there was such a stark contrast for the 5-star reviews, we won't necessarily find that for the rest of the reviews. 
