# Ecommerce Text Classification Using LSTM 
This project applies Natural Language Processing (NLP) techniques to classify text data in an ecommerce context. Specifically, it leverages a Long Short-Term Memory (LSTM) neural network to perform text classification tasks on user-generated content, such as product reviews or queries. 

## Project Overview

Ecommerce platforms often deal with vast amounts of user-generated content, which can include product reviews, descriptions, or customer inquiries. The goal of this project is to classify this text into predefined categories using deep learning.

This project uses LSTM, a type of recurrent neural network (RNN) architecture, which is particularly effective at capturing long-term dependencies in sequential data like text. The model is trained on labeled ecommerce data to predict categories or sentiments based on the text input.


## Key Features
- **Text Preprocessing**: Tokenization, stopword removal, and word embedding techniques (such as Word2Vec or GloVe).
- **LSTM-based Model**: A deep learning model to classify the processed text data.
- **Evaluation**: Performance metrics like accuracy, precision, recall, and F1-score are computed to assess the model.
- **Future Work**: The project will be deployed using FastAPI, Streamlit, or other deployment tools.


## Data
The dataset used for this project consists of ecommerce-related text data. The text is labeled into different categories (e.g., product type, review sentiment, customer query type). Specific preprocessing steps like cleaning, tokenization, padding, and vectorization have been applied.

## Model Architecture
The LSTM network consists of the following:
- An embedding layer to convert text input into dense word vectors.
- LSTM layers to capture sequential dependencies in the text.
- Fully connected (Dense) layers with softmax activation for multi-class classification.
