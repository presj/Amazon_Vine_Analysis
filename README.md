# Amazon_Vine_Analysis

Overview of the Analysis

In deliverable 2 we re-created dataframes, in particular, where Vine reviewers could be identified as paid or unpaid.  The analysis performed would determine if having a paid Vine review made a difference in the percentage of 5-star reviews.  PySpark was used to assess if there was any bias toward favorable reviews among Vine members.

Results

How many Vine reviews (paid) and non-Vine reviews (unpaid) were there?

The total number of paid reviews was 285 and the total number of unpaid reviews was 31,545.

![image](https://user-images.githubusercontent.com/100803302/174488898-4a330d33-b528-4935-b2a2-738f51da383e.png)

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

There were 163 5-star Vine reviews and 14,614 5-star non-Vine reviews.

![image](https://user-images.githubusercontent.com/100803302/174489241-051dbf21-ea7f-46a6-b3d5-56d90f921c8c.png)

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

57% of Vine reviews were 5-star and 46% of non-Vine reviews were 5-star.

![image](https://user-images.githubusercontent.com/100803302/174489345-e41eab65-0784-42aa-af43-ebc4c5c1704c.png)

Dataframes of Vine and non-Vine reviews:

![image](https://user-images.githubusercontent.com/100803302/174489403-6c6e8470-d30a-42e2-918b-22c3a373ae39.png)

Summary

Based on the findings, the pool of Vine reviewers show slightly more positivity bias in their reviews than the pool of non-Vine members. However, this can be misleading because the total number of Vine and non-Vine reviewers is 31,830 and the total number of Vine reviewers is 285.  This means that all Vine reviewers make up less than 1% of reviews. Further analysis of randomly selected products, reviewed by both groups, may support that no bias can be concluded.
