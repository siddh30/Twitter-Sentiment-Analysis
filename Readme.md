# Twitter Sentiment Analysis 
<img src="https://github.com/siddh30/Twitter-Sentiment-Analysis/blob/main/images/twitter.png" width="350">




## Goal
Understanding and Predicting Tweet Sentiments across various entities
 (topics)
 
## Step 1: Data
This is a Kaggle dataset (https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis) with two files training.csv and validation.csv
Features :- Entity, Tweet ID, Tweet and Sentiment (Positive, Negative, Neutral and Irrelevant)

## Step 2: EDA
Discovered Insights such as:

1. What is the most common sentiment across all tweets?
   - Most Tweets are of **Negative Sentiment**. Positve and Neutral Tweets closely follow.
<p align = 'center'> <img width="800" img height= "500" alt="submission" src="https://github.com/siddh30/Twitter-Sentiment-Analysis/blob/main/images/Sentiment_distribution.png"> </p>


2. What are the most commonly tweeted topics?
   - Most Tweets revolve arround Gaming, Tech and Social Media in this Dataset
   <p align = 'center'> <img width="800" img height= "500" alt="submission" src="https://github.com/siddh30/Twitter-Sentiment-Analysis/blob/main/images/Entities.png"> </p>


3. Ten Most commonly talked about topics and their overall sentiment?
   <p align = 'center'> <img width="500" img height= "400" alt="submission" src="https://github.com/siddh30/Twitter-Sentiment-Analysis/blob/main/images/Topicwise_Sentiment.png"> </p>



## Step 3: Modeling
Used a Sentence Transformer with a Random Forest Classification Head to classify sentiments
<p align = 'center'> <img width="500" img height= "200" alt="submission" src="https://github.com/siddh30/Twitter-Sentiment-Analysis/blob/main/images/classification_report.png"> </p>


## Step 4: Model Expainability 
Used Lime a Model Agnostic Explainer to explain word level impact on different classes of the model
<p align = 'center'> <img width="1200" img height= "400" alt="submission" src="https://github.com/siddh30/Twitter-Sentiment-Analysis/blob/main/images/Negative.png"> </p>

<p align = 'center'> <img width="1200" img height= "400" alt="submission" src="https://github.com/siddh30/Twitter-Sentiment-Analysis/blob/main/images/Positive.png"> </p>

<p align = 'center'> <img width="1200" img height= "400" alt="submission" src="https://github.com/siddh30/Twitter-Sentiment-Analysis/blob/main/images/Neutral.png"> </p>


 
