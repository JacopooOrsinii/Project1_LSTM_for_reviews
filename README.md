# Project2_LSTM_for_reviews
This repository contains an implementation of a Long Short-Term Memory (LSTM) neural network designed to classify text reviews as either positive or negative. The project leverages the LSTM architecture's ability to capture temporal dependencies in sequences, making it particularly effective for sentiment analysis tasks. Sentiment analysis is a crucial task in natural language processing (NLP), where the goal is to determine the sentiment behind a given piece of text. This project utilizes an LSTM model, which is well-suited for handling the sequential nature of text data, to classify reviews from a dataset into positive or negative categories.

## The goal
The goal of this project is to train an LSTM neural network to perform binary classification of Amazon reviews as either positive or negative. The dataset consists of two columns: the review text and the corresponding rating. Each review is represented as a numerical vector, where each word in the review is mapped to a 300-dimensional vector. These vectors are generated using three different word embedding models: Word2Vec, FastText, and GloVe.

## The structure
The code's project is divided into 5 parts:
- **Loading the necessary packages and files**: this section handles the import of necessary libraries and tools required to run the code, as well as loading the dataset, which is sourced from this [link](https://amazon-reviews-2023.github.io/) .
- **Preprocessing the reviews**: in this part, each word in the reviews is transformed into a numerical vector. These vectors capture semantic similarities, meaning that similar words will have similar vectors. The embedding models used include Word2Vec, FastText, and GloVe.
- **Embeddings**: this part of the code allows to associate to each word a vector, which will have similar numbers for similar vector, as mentioned before, the word embeddings models that has been used are Word2Vec, FastText and GloVe.
- **Combining the embeddings**: the three embeddings are merged to create a dictionary, where each word is associated with a 300-dimensional vector.
- **LSTM model**: this section involves the implementation of the LSTM neural network, which is used for the binary classification of the reviews. 
