# Amazon_Vine_Analysis

## Overview

The purpose of this analysis was to see if any bias is introduced in product reviewing with Amazon's Vine reviewing program. I chose the musical instrument data set which includes products like pianos and guitars as well as microphones and other music equipment. We filtered the reviews to only show reviews that buyers/customers found most helpful on the review page.

## Results

I took the liberty of creating a summary dataframe to illustrate my results (pictured below)...

![df](Pics/vine_analysis_df.png)

How many Vine reviews and non-Vine reviews were there?

- In this data set, there were only 60 Vine reviewers leaving 14,477 unpaid

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

- 34 paid reviews were five stars and 8212 unpaid were 5 stars

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

- Each subset of reviews had virtually identical numbers of 5 star reviews, paid or unpaid: around 56%

## Summary

It doesn't seem as if there's any bias at all with the Vine program in musical instruments; at least when filtering out unhelpful reviews. 

However, it seemed like there were a very small number of Vine reviewers in this dataset. Most musical instrument companies might not have the marketing budgets to pay for reviews on Amazon and therefore skew the results of this test. Having said that, the similarity of 5 star reviews in comparison to the general population is startlingly similar. Reviewers seem to take their products very seriously and are just as critical and complimentary whether paid or not. It might be helpful too look at reviews overall because every review contributes to the overall average rating of a product on Amazon and I believe people pay just as much attention to that than they do individual reviews in some cases. 
