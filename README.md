I will scrape reviews from BestBuy.com. I will also include the .ipynb and .md versions of my work + the following two scatterplots as part of my output.
  - scatterplot with length on the x axis, total on the y axis
  - scatterplot with length on the x axis, nethelpful on the y axis

My goal is to scrape 1000 reviews that were posted in the reviews page of my assigned item. The format of my output should be a dataframe with the following columns/format:

|variable | description
| :---    |    :---   |
username |  the user name of the reviewer
review | the review content
rating | the rating (out of 5) left by the reviewer
helpful | the number of votes received on the review indicating that the review is helpful
unhelpful | the number of votes received on the review indicating that the review is unhelpful
net | the absolute value of the difference between "helpful" and "unhelpful" votes
nethelpful | the difference between "helpful" and "unhelpful" votes
total | total number of votes (helpful + unhelpful) received
length | length of the review, defined as the number of characters in a review (including whitespace)




