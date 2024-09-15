# Sentiment Analysis on Twitter Data

This project performs sentiment analysis on real-time tweets using **VADER** sentiment analyzer and **Logistic Regression** for classification. Tweets are classified into three categories: **positive**, **negative**, and **neutral**.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Installation](#installation)
3. [Dataset](#dataset)
4. [Model Training](#model-training)
5. [Model Evaluation](#model-evaluation)
6. [Saving the Model](#saving-the-model)
7. [Usage](#usage)
8. [License](#license)

## Project Overview
This project focuses on classifying tweets as positive, negative, or neutral using real-time data from Twitter. It uses **Tweepy** to collect the tweets and **VADER** for sentiment analysis. A **Logistic Regression** model is built for the sentiment classification task.

## Installation
To run this project, you need the following libraries installed:

```bash
!pip install tweepy
!pip install nltk
!pip install vaderSentiment
!pip install scikit-learn
