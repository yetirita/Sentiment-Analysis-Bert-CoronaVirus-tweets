# Sentiment-Analysis-Bert-CoronaVirus-tweets
This is the group project of class MSBD6000I

Sentiment Analysis on CoronaVirus tweets based on Bert

## Introduction
### Background
Covid-19 2019 (COVID-19) is an infectious disease caused by a newly discovered coronavirus in 2019. Because of its high mortality rate and high infectivity, it has affected 213 countries, caused 10 million infections and 1 million deaths around world. Coronavirus hasan unprecedented impact on the world economy and policies. It is critical tounderstand how people view ang respond to the government policies. And knowing people’s attitudes, perspectives and their behaviors could contribute to theepidemic prevention work afterwards.

The information gainedfrom social media can even help predict the spread and growth of diseases. Twitter is a popular social networking platform which with 330 million monthly activeusers, 500 million tweets per day. Compared with news, Twitter is more dynamicand democratic, which has been widely used in social media and language processing research. For example, in 2014, some researchers used twitter’s datato study the Ebola. And the consequence is that compared with the official newsarticle, Twitter’s text can help researchers have better understand in what isreally going on in the real crisis.

### Dataset
https://www.kaggle.com/datatattle/covid-19-nlp-text-classification.

It has 5 classes of emotion, including Extremely Negative, Negative, Neutral, Positive, Extremely Positive.

### Environment
Google Colab with Tesla K80 GPU

Frameworks: Tensorflow, Kashgari, etc.


## Main Tasks
Visualization includes data analysis, wordclouds, word frequency, etc.

Classification includes traditional deep learning models and feature-baased BERT (baseline).

### Evaluation
Evaluation includes loss(tensorboard), accuracy, confusion matrix

Accuracy of 5-class Classification with BERT: 0.87

Accuracy of 3-class Classification with BERT: 0.92

Accuracy of 3-class Classification with based on the model of 5-class: 0.933

Accuracy of traditional deep learning models (5-class classification):

| Model      | 3-class classification     | 5-class classification     |
| ---------- | :-----------------------:  | :------------------------: |
| BiGRU      | 57.93%                     | 76.07%                     |
| BiLSTM     | 57.93%                     | 76.07%                     |
| CNN        | 57.93%                     | 76.07%                     |
| CNN+GRU    | 57.93%                     | 76.07%                     |
