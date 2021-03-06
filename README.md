# Amazon_Vine_Analysis

## Overview of the analysis: 
The purpose of this project is to analyze the reviews of Amazon's Vine Program. This program is a paid program, where manufactuerers can pay to receive reviews from their products. Their products are provided to Amazon Vine members who are required to publish a review. One can only be a Vine Reviewer by invite only. Amazon considers Vine Reviewers some of the most trusted reviewers on their website. This project aims to determine if there is any bias toward favorable reviews from Vine members. 

## Results: 

### How many Vine reviews and non-Vine reviews were there?
There were a total of 43574 reviews for outdoor products. Of those 21372 reviews were 5 star ratings. Overall, there were far more reviews for paid vs. unpaid users. This makes sense because to become a Vine Reviewer, you must be selected. 

#### Total Count of Paid Reviews
![paid_reviews](amazon_review_screenshots/paid_reviews.png)

#### Total Count of Unpaid Reviews
![total_unpaid_reviews](amazon_review_screenshots/total_unpaid_reviews.png)

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

When considering the costs to have your company join the Amazon Vine Program, its important to know your reviewers aren't being swayed by receiving perks/payment from performing reviews. If this was the case for Vine Reviewers, we would possibily see a difference in 5-star reviews between paid and unpaid reviewers. However, through further review of the outdoor products reviews, there was not huge different between the porportion of 5 star reviews. 

#### Paid 5 Star Reviews
![5_star_paid](amazon_review_screenshots/5_star_paid.png)

#### Unpaid 5 Star Reviews 
![5_star_unpaid](amazon_review_screenshots/5_star_unpaid.png)

5 star reviews for both unpaid and paid reviewers accounted for about 52% of reviews. 

### Summary: Is any positivity bias for reviews in the Vine program? 

5 Star reviews aren't the only useful metric to dive into. Other rated reviews can provide insight to whether or not there is a positivity bias among Vine Reviewers. 

#### All Star Reviews for Paid Reviewers
![rating_paid](amazon_review_screenshots/rating_paid.png)

#### All Star Reviews for Unpaid Reviewers 
![rating_unpaid](amazon_review_screenshots/rating_unpaid.png)

Although, the 5 star ratings for both paid and unpaid reviewers have a similar percentage of the overall reviews, the other star ratings differ a bit more. If we consider 4 & 5 star reviews to be positive reviews, positive reviews for paid reviewers account for 82.23% of reviews. However, for unpaid reviewers, it only accounts for 71.21% of reviews. 

Let's consider negative reviews to be 1 & 2 star reviews. Negative reviews account for 2.16% of reviews for paid reviewers, while accounting for 19.4% of unpaid reviewers. Looking at the difference between positive and negative reivews, I would say there is a higher chance for a negative review to come from an unpaid reviewer vs. a paid one. With the difference in overall positive reviews being higher for paid reviewers, and negative reviews for unpaid reviewers to higher, there could be a positive bias with the reviewers in the Vine Program. However, this doesn't seem to be the case specifically for 5 star reviews. 









