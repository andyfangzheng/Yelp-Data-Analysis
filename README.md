# Yelp-Data-Analysis
In this case, we want to compare the accuracies of Textblob and two logistic regression models which could predict the stars that 
customers would give based simply on their review contents, but not the actual stars they give.

Since the review dataset is too large and we cannot process the whole data set in our PC, we decided to filter the most convincing 
and useful reviews from the dataset, so we filter reviews with "useful" greater or equal to 10 in the first 1,000,000 reviews.

Besides the stars itself, we suggest Yelp to take a look at the reviews text and improve the rating system to avoid unfair ratings. 
