# AmazonProductReviewAnalysis
This is done as part of course project for Data engineering at scale course DA231O at IISc for M.Tech.

As part of this, sentiment analysis of user reviews (obtained 72% accuracy on 360k data points), trained on 1.8Mn rows,
product portfolio based on user ratings, and recommendation systems using collaborative filtering (ALS algorithm) and content based filtering using (cosine similarity b/w titles) are done.

Dataset for references:
1. https://www.kaggle.com/datasets/bittlingmayer/amazonreviews - For sentiment analysis
2. https://cseweb.ucsd.edu/~jmcauley/datasets/amazon_v2/#code
a.Total review data containing review text, review summary, overall (Sizes of the order of GBs - books data is 6.5GB)
b. K-Core data - Each product will have K ratings given by users (It's a shortened version of 1st data set)
c. Metadata of the products reviewed. Contains some useful columns like features, also_buy etc.
The data is further split into categories (Video games, Books, kindle review, software, clothes etc)¶

