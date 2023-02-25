# Amazon-Vine-Analysis
## Overview of the Project
We will look at Big Data and Cloud Services for this week's project. Big Data is data that has more variety and is generating at high volumes quickly. Spark has become the number one leading technology for handling big data. This will allow us to process and analyze data quickly and at a massive scale. We will also use Google Colab since it is hosted in the cloud. This also makes it easier to read datasets from the cloud. Our data will be pulled from Amazon's Simple Storage Service (S3).
## Results
For us to determine if there was a bias against Vine Reviews, we created a data frame from our Amazon review data that had 6 columns:

review_id: The unique ID of the review. star_rating: The 1-5 star rating of the study. helpful_votes: Number of helpful votes. total_votes: Number of total votes the consideration received. Vine: The review was written as part of the Vine program. verified_purchase: The review is on a verified purchase. We filtered the data frame to retrieve rows where the total_count was greater or equal to 20 and also screened to show reviews that are more likely to be helpful. We created two more data frames based on if the review was a Vine review (paid) or a non-Vine review (unpaid).

Here are the results of the total number of reviews, the number of 5-star reviews, and the percentage of 5-star reviews for the two types of thinking (paid vs. unpaid)
Total Number of Reviews

![paid reviews](https://user-images.githubusercontent.com/113754027/221382869-d903d461-ebc8-42c7-8a0c-cc733a92bb89.png)
the total number of paid reviews would be 94

Non Paid Reviews
![non paid reviews](https://user-images.githubusercontent.com/113754027/221382931-df0a3778-d236-467d-b91c-0a375c9a6179.png)
40,471
Number of 5 stars 
Vine 5 stars in the picture earlier for paid 5 stars that number is 48

and total none vine 5 stars 15,663
Percentage paid that number is 51%
and non paid is 38%

##Summary
After reviewing the results comparing the Vine vs. Non-Vine reviews, there is no bias for studies in the Vine program. As seen in the images above, 51% of Vine members' reviews were 5-star, and 38% of Non-Vine reviews were 5-star. The number of Vine reviews total compared to Non-Vine reviews is significantly less, though.
