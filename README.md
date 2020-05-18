Entry to the Kaggle Real or Not? NLP with Disaster Tweets Competition

This notebook is an effort to combine the predictions of two different algorithms. Firstly, a prediction is made with a binomial naive Bayes algorithm using only the tweet text. The results of this prediction is used as a new feature in the original dataset. The first word of the keyword field is then also selected as a new feature. For the final prediction, the features (MultinomialNB_predict, keyword, text length) are used, and a light gradient boosting machine is used with KFold cross validation.
