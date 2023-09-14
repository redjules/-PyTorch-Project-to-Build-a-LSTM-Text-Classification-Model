# Project Description

# Overview

Long short-term memory(LSTM) is a recurrent neural network architecture(RNN) used in the field of deep learning. These architectures are capable of learning long-term dependencies faced by recurrent neural networks. LSTMs have feedback connections which makes them different from the traditional feed-forward neural networks. LSTMs are particularly good at text data, speech, and time series. 

In this project, an LSTM model for classifying the review of an app on a scale of 1 to 5 based on the feedback has been built in PyTorch. 


# Goal

To understand the  working of LSTM 

To classify the review of an app on a scale of 1 to 5 using LSTM


# Data Description

The dataset contains the reviews and the ratings of the app. The dataset has a score column and content column. The score columns have a number range between 1 to 5 based on the content column. 


# Tech Stack

- Language: Python

- Libraries: pandas, tensorflow, matplotlib, sci-kit learn, nltk, numpy, pytorch


# Approach

- Data Preprocessing

  - Lowering Text, removing punctuation, removing links 

  - Balancing classes

  - Tokenizing the text

  - Scaling

- Model Training

   - Training LSTM model in PyTorch

- Model Evaluation

  - Evaluation of model on test data


