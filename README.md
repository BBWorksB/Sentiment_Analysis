# Exploring Tweet Sentiment Analysis

![Sentiment Analysis](shubham-dhage-t0Bv0OBQuTg-unsplash.jpg)

## 1. Business Understanding

#### Introduction

Unlocking the power of sentiment analysis within the realm of customer feedback on Twitter is a pivotal step towards enhancing corporate growth, informed decision-making, and profit optimization. In this project, we embark to delve deep into the Twitter customers' sentiment concealed within user-generated feedback directed at companies. Will achieve this through utilizing Natural Language Processing (NLP) techniques, aimed at unraveling the sentiment spectrum and its profound implications for businesses. Will use data from dataworld.

#### Main Objective

- Build a robust sentiment analysis model to rate the sentiment of tweets based on their content.

#### Overview

In this project, we aim to create a multiclass classifier for sentiment analysis of tweets. Our primary objective is to understand and rate the sentiment of tweets, categorizing them into three classes: positive, neutral, and negative. This analysis will enable businesses and individuals to gauge public sentiment, monitor brand perception, and make informed decisions.

#### 2. Experimental Design

- Data understanding - importing necessary libraries, loading the data and get general understanding of the dataset.
- Data Preprocessing - treat the data, clean it and structure the tweet data to be ready for analysis.
- EDA / Visualizations - Create visuals, graphs to enhance understanding of the data.
- Model building - Use deep learning models to construct a sentiment model.
- Model evaluation - asses the models perfomance using relevant metrics in this project will use accuracy.

#### 3. Benefits of the project

- Facilitate data-driven decision-making for businesses.
- Enhance marketing strategies by understanding customer sentiment.
- Monitor and manage brand perception.
- Stay informed about public opinion on various topics and events.

## 5. Conclusion

- In this project, we explored various models for sentiment analysis on text data. We started with a baseline model using a neural network (NN) to preserve sequence information in text data.
- We then experimented with more advanced models, including LSTM and Tuned Bidirectional LSTM, in an effort to improve accuracy. While the latter showed promise with better accuracy, it exhibited overfitting issues.
- Based on our findings, tuned LSTM appears to be a suitable model for this dataset, achieving an accuracy of approximately 82% after around 4 epochs of training.

## 6. Recommendation

- To further enhance model performance, consider exploring state-of-the-art models like BERT (Bidirectional Encoder Representations from Transformers) for sentiment analysis. BERT-based models have exceptional capabilities in natural language understanding tasks and may lead to even more accurate sentiment analysis results.
