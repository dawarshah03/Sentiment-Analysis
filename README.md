# Twitter Sentiment Analysis Using Naive Bayes

I made a sentiment analysis project using Naive Bayes in Python.

It checks if a tweet is either positive or negative. I removed the neutral ones to keep it simple with just two results.

First, I cleaned the tweets by removing links, usernames, hashtags, and symbols. Then I changed everything to lowercase so the model understands better.

I used TfidfVectorizer to convert the text into numbers. After that, I split the data into training and testing using train_test_split.

Then I trained the model with Multinomial Naive Bayes and tested how well it works.

# The accuracy I got was 0.83625 which means it's around 83.6% correct.

I also tried it with new tweets like "Its Amazing!" and it gave the correct prediction.

The dataset and full code are in this repo.
