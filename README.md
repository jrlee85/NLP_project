# NLP_project

Personal project based on the Disaster Tweets Kaggle Competition. The task was to use natural language processing techniques to perform binary classification on tweets.

I began with some exploratory analysis and simple visualisations to get a better understanding of the data. I then used both Bag of Words and Term Frequency-Inverse Document Frequency to transform the tweets into vectors that could be used with different machine learning models.

I tested Linear (Ridge) Classification, Logitsic Regression (with stochastic gradient descent), Support Vector Classification and Multinomial Naive Bayes Classification. I also experimented with using unigrams and bigrams.

Finally, I used Bidirectional Encoder Representations from Transformers (BERT) to see if this could give improved results. After some experimentation with different learning rates, I was able to achieve an F1 score of 0.83481, resulting in a true position of 80th on the Kaggle public leaderboard.

The notebook makes use of several libraries, including NumPy, Pandas, Sklearn, NLTK, Scipy and Transformers.
