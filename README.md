# Classify Spam Emails using Machine Learning Models

This is a project that I conducted to develop my skill and knowledge about Natural Language Processing (NLP) using Python. Data that I used was from [kaggle](https://www.kaggle.com/chandramoulinaidu/spam-classification-for-basic-nlp). It is a nice dataset for beginner (like me) to implement NLP techniques (such as tokenization, lowercasing, lemmatization, filtering stopwords, bag of words, and TF-IDF) in a real use case.

The case in this data is to predict whether a message in an email is spam or not. For prediction purpose, we can use different kinds of machine learning models to classify and predict a spam email given its raw text messages. I personally used logistic regression, random forest classifier, and light gradient boosting machine (LGBM) classifier as my main machine learning models in this project. It turns out that the LGBM classifier was my best model to predict spam emails by using the data from TF-IDF results. It has accuracy of 0.99 and AUC of 0.99.

Check out the python notebook to see all of my approach in this project. Thank you!