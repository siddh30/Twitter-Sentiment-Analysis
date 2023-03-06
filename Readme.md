# Twitter Sentiment Analysis 
A Mini Weekend Projects

Goal of the project : Understanding and Predicting Tweet Sentiments across various entities
 (topics)
 
## Step 1: Data
This is a Kaggle dataset (https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis) with two files training.csv and validation.csv
Features :- Entity, Tweet ID, Tweet and Sentiment (Positive, Negative, Neutral and Irrelevant)

## Step 2: EDA
Discovered Insights such as:

Q1. What is the most common sentiment across all tweets?
Attach an Image
Most Tweets are of **Negative Sentiment**. Positve and Neutral Tweets closely follow.


Q2. What are the most commonly tweeted topics?
Attach an Image
Most Tweets revolve arround Gaming, Tech and Social Media in this DataSet


Q3. Ten Most commonly talked about topics and their overall sentiment?
Attach an Image


## Step 3: Modeling
Used a Sentence Transformer with a Random Forest Classification Head to classify sentiments


## Step 4: Model Expainability 
Used Lime a Model Agnostic Explainer to explain word level impact on different classes of the model
Attach Images