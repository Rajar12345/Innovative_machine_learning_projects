# Fake News Detection Using Logistic Regression

This project demonstrates how to build a Fake News Detection model using a Logistic Regression classifier and TfidfVectorizer for text feature extraction. The model classifies news as **Real** or **Fake** using a dataset from Kaggle.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Installation](#installation)
3. [Dataset](#dataset)
4. [Model Training](#model-training)
5. [Model Evaluation](#model-evaluation)
6. [Saving the Model](#saving-the-model)
7. [Usage](#usage)

## Project Overview
Fake news detection is a growing challenge in today’s media landscape. This project builds a machine learning model to identify fake news using Logistic Regression. It uses text features obtained through **TF-IDF** (Term Frequency-Inverse Document Frequency) for classification.

## Installation
To run this project, you'll need to set up Kaggle API access and install necessary libraries. Follow these steps:

### Step 1: Setup Kaggle API in Google Colab
1. **Sign up** for a Kaggle account if you don’t have one.
2. Install the Kaggle API:

   ```bash
   !pip install kaggle
