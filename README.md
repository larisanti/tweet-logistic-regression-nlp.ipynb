# Tweet Sentiment Analysis with Logistic Regression Visualization

This notebook documents a lab exercise where I explored logistic regression for tweet sentiment analysis, a key concept from the "Natural Language Processing with Classification and Vector Spaces" course. It features key visualizations, including a scatter plot of tweets based on their positive and negative features, and the decision boundary of a trained logistic regression model.

---
I applied the following NLP techniques:
* Data Loading & Exploration: The notebook loads positive and negative tweet samples from the NLTK twitter_samples dataset, with a total of 8000 tweets for training.
* Text Preprocessing: Tweets undergo a cleaning process that includes removing stock tickers, old-style retweet text, hyperlinks, and hashtag symbols. Tokenization is performed using TweetTokenizer, followed by removal of English stopwords and punctuation. Porter stemming is also applied to words.
* Feature Extraction and Model Loading: A build_freqs function creates a dictionary of word frequencies, which is essential for feature extraction. The notebook then loads extracted features (bias, positive, negative) from a CSV file and a pre-trained logistic regression model's parameters (theta).
* Data Visualization: The core visualizations include a scatter plot displaying tweets based on their positive and negative features, with positive tweets in green and negative in red. The decision boundary of the trained logistic regression model is also plotted as a gray line, along with green and red arrows indicating the direction of positive and negative sentiment, respectively.
  
---
For details, please refer to the [Jupyter Notebook file.](https://github.com/larisanti/tweet-logistic-regression-nlp.ipynb/blob/main/tweet_logistic_regression_nlp.ipynb)
