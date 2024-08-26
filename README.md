# Project2_LSTM_for_reviews
This repository contains an implementation of a Long Short-Term Memory (LSTM) neural network designed to classify text reviews as either positive or negative. The project leverages the LSTM architecture's ability to capture temporal dependencies in sequences, making it particularly effective for sentiment analysis tasks. Sentiment analysis is a crucial task in natural language processing (NLP), where the goal is to determine the sentiment behind a given piece of text. This project utilizes an LSTM model, which is well-suited for handling the sequential nature of text data, to classify reviews from a dataset into positive or negative categories.

## The goal
The goal of this project is to train an LSTM neural network to perform binary classification of Amazon reviews as either positive or negative. The dataset consists of two columns: the review text and the corresponding rating. Each review is represented as a numerical vector, where each word in the review is mapped to a 300-dimensional vector. These vectors are generated using three different word embedding models: Word2Vec, FastText, and GloVe.

## The structure
The code's project is divided into 5 parts: \
- Loading the necessary packages and files: here the preliminary tools to make the code run are downloaded, together with the dataset, whcih has been taken at the following link https://amazon-reviews-2023.github.io/ \
- 
