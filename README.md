I will scrape reviews from BestBuy.com. This is the link to the item that I am going to scrape:

https://www.bestbuy.com/site/reviews/apple-airpods-with-charging-case-2nd-generation-white/6084400?variant=A&skuId=6084400

My goal is to scrape 1,000 reviews that were posted in the reviews page of my assigned item. The format of my output should be a dataframe with the following columns/format:

username: the user name of the reviewer
review: the review content
rating: the rating (out of 5) left by the reviewer
helpful: the number of votes received on the review indicating that the review is helpful
unhelpful: the number of votes received on the review indicating that the review is unhelpful
net: |helpful - unhelpful| i.e., the absolute value of the difference between "helpful" and "unhelpful" votes
nethelpful: helpful - unhelpful i.e., the difference between "helpful" and "unhelpful" votes
total: total number of votes (helpful + unhelpful) received
length: length of the review, defined as the number of characters in a review (including whitespace)

I will also include the .ipynb and .md versions of my work + the following two scatterplots as part of my output.
- scatterplot with length on the x axis, total on the y axis
- scatterplot with length on the x axis, nethelpful on the y axis
