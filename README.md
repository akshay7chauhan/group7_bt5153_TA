# group7_bt5153_TA
BT 5153 Project - Text Mining of Trip Advisor Reviews (Singapore) - Group7

Data -- sample files uploaded
-------------------------------

TA_data_subset.csv -  Original file

Sent_score_data_subset.csv -  Added sentiment scores to review body and review titles

cleaned_data_subset.csv - contains cleaned review text obtained after running the code in data_preprocessing.ipynb

topic_data_subset.csv - obtained after using LDA for topic scoring all reviews based on generated and labelled topics.

EDA code files
---------------

EDA_basic.ipynb - Understanding the dataset

EDA--wordcloud.ipynb - 

EDA-User & Attractions.ipynb - 

Review Text cleaning
--------------------
Building a data preprocessing pipeline to remove noise and improve future use of review text as input for Modelling.

data_preprocessing.ipynb

Sentiment Scoring
------------------
Using vader sentiment to assign sentiment score to the review body and review title. These serve as valuable features for the
rating prediction and topic modeling excercise.

Sentiment scoring.ipynb 

Predicting Ratings
------------------
To ensure that all the terms used in this analysis contributed to tourist sentiment and topic modelling it was essential to have a 
good model prediction for ratings.

ML Algorithms used:

1. Logistic Regression 

Logistic regression baseline.ipynb

2. SVM

SVM.ipynb

3. Naive Bayes + BOW

NB.ipynb

Topic Modelling
----------------


1. LDA using TFIDF vectorizer

LDA_body_type.ipynb

Recommender systems
-------------------
Buidling User profiles by combining Country of origin and trip type data fields.
Used cosine similarity based on the ratings for all attractions by profile to establish similarity.
Building Recommendation system on top of the above knowledge using Nearest neighbour algorithm.

1. Cosine similarity + Nearest Neighbour Algorithm

TA Rec system.ipynb

