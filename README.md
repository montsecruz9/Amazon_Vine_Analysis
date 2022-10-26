# Amazon Vine Analysis
## Overview of the project
The purpose of this project is to analyze Amazon reviews written by members and non-members of the Amazon Vine program. This program is a service that allows Amazon sellers to provide products to the Amazon Vine program members, who will then be required to publish a review. We're gonna determine if there is any bias toward more positive reviews from Vine members. For this project, we're gonna analyze an Amazon dataset for pet products reviews.

## Results
- Vine members reviews

![image](https://user-images.githubusercontent.com/104812189/197932696-6c1504b8-afd6-4c28-826b-67b8dc2f46b2.png)

There were a total of 170 reviews from the Amazon Vine program members. From this total, a 35.3% of the reviews (60 reviews) gave a 5-star rating to the products.

![image](https://user-images.githubusercontent.com/104812189/197933607-b9bb3ac5-5a41-4b16-8a13-a21e85e47ffd.png)

- Non members reviews

![image](https://user-images.githubusercontent.com/104812189/197933806-2874bfbd-2695-466d-b5fc-376959c0b33a.png)

There were a total of 37840 reviews from non members. From this total, 20612 reviews (54.5% of the total) gave a 5 star rating. 

![image](https://user-images.githubusercontent.com/104812189/197933869-0d17bc7e-ea50-4b64-a91c-76b07398a82e.png)



## Summary
From the 170 reviews from Amazon Vine members, 35.3% gave a 5-star rating. From 37840 reviews from non members, 54.5% gave a 5-star rating. We can conclude that there is no bias towards positive reviews from members of the Vine program. To support this statement, we can add one more analysis, where we only consider the 'helpful votes' from the dataset, instead of the percentage of helpful_votes/total_votes.  
