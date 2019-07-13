## Problem Statement : 
Create a classification model that will predict which subreddit the post is from.


## Executive Summary:

Many people assume that Psychology and Sociology subreddit pages are very similar to each other. Through this reddit classification we can showcase how different these 2 subreddit pages are.


## Conclusion: 

After the text was cleaned and tokenized, we used the pipelines and GridCV to find out which vectorizer and parameters gave the most accurate subreddit predictions. We observed overfitting for the countvectorizer and logistic regression model, while the other models worked equally well. Therefore, the models were evaluated based on their precision scores. The evaluations concluded that the tfidf vectorizer together with the Multinomial Naive Bayes gave the highest precision values.Out of the 374 data points in the test dataset only 67 of the subreddit were classified wrongly. Therefore, we suggest that the tfidf and the Multinomial NB is a good predictor for classifying the subreddit categories. We have to take note that the current model only has two different subreddits to classify from. Therefore, this same model might not be useful in predicting when there are more than 2 subreddit categories.
