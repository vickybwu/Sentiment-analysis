# Sentiment-analysis

This project focuses on exploring the efficiency of a simple sentiment classification task using multiple natural language processing methods including different word vectorization techniques, and various machine learning models, including Naïve Bayes, KMeans, Logistic Regression, SVM, LDA and RNN, by discussing the application and advantages versus disadvantages with each of these methods.


The project is done by using a real commercial customer review dataset for an online clothing store, which can be accessed through https://www.kaggle.com/nicapotato/womens- ecommerce-clothing-reviews. The dataset includes 23486 rows and 10 feature variables. Each row corresponds to a customer review, and a description for each feature variable can be found on the website.

The classification task performed in this research utilized only two of the ten feature variables in the dataset: “Review Text” and “Recommended IND”. The “Review Text” variable is used as the predictor while the “Recommended IND” variable is used as the labels. The goal of the task is to classify each review into either “recommended” or “not recommended” category based on the sentiment expressed in the review body. 

To be able to use statistical models for our classification task, text data needs to be
converted into numeric values. The following steps were taken to process the review body text: 
1) Data sampling and shuffling
2) Word segmentation (Tokenization)
3) Remove punctuation and numbers
4) Remove words of less semantic meaning Word lemmatization
5) Word vectorization
