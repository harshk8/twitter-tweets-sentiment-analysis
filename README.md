NLP - Sentiment Analysis

Reference from: Analytics Vidhya course doc.

Problem: We have some tweets of some users what they think about our product. we have to find out what peoples opinion, its positive or negative.

Following steps we will follow here:

1. Understanding the problem statement.
2. Tweets preprocessing and cleaning.
3. Story generation and visualization of tweets.
4. Extracting features from cleaned tweets.
5. Model building: Sentiment Analysis.

#1 Problem Statement:
Problem statement should be the main aim to understand first before doing anything.

#2 Cleaning Data:
Cleaning data should eb second step before moving with data. Step to clean the noise, words those are less relavent to find the sentiment of tweets such as punctuation; special character; numbers; etc.

##A. After removing punctuation; special character; numbers; small words also those words which are not having any weightage in our dataset.

##B. Tokenization: Break all the sentences in tokenized form.

##C. Stemming words: Those words which are in having past or future verbs in it. Should be replace with its original form without any verb form.
Ex. Playing, plays will be replace with "play"

#3 Story generation and visualization:
We should not limit ourset with only few question but we should explore it with new methods questions too. Few of questions are as follows:

##A. Find most common words.
##B. find most common words in negative and positive tweets respectively.
##C. How many hashtags in tweets. 
##D. Is their any trending hashtag involved.
##E. If yes, then check is that trending hashtag is relavent to our words sentiment.

Extracting feature from cleaned tweets by using assorted techniques:
---> Bags-of-words
---> IF-IDF
---> Word Embedding