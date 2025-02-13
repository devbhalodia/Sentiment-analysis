# Sentiment Analysis using Two Methods
1. Integer Encoding with Neural Networks
2. Embedding Layer with Neural Networks
   
# Project Structure
-> Sentiment_Analysis_using_Integer_Encoding.ipynb: Implements sentiment analysis using integer encoding for text data preprocessing.
-> Sentiment_Analysis_using_Embedding.ipynb: Implements sentiment analysis using an embedding layer for text vectorization.

# Dataset
The dataset used in both approaches contains labeled text data for binary sentiment classification (e.g., positive or negative sentiment). Text preprocessing steps include tokenization and preparing data for input into neural networks.

# Methods
1. Integer Encoding
-> Text is converted into integer sequences using integer encoding.
-> The model architecture includes:
-> An input layer that takes integer-encoded sequences.
-> Dense layers for processing the input data.
-> A final output layer for binary classification.
2. Embedding Layer
-> The text data is processed using an embedding layer to convert words into dense vector representations.
-> The model architecture includes:
-> An embedding layer to learn word representations.
-> Additional layers for feature extraction and classification.
-> A final output layer for binary classification.

# Performance
Both methods are evaluated using accuracy and loss metrics to compare their performance. The results show the effectiveness of using an embedding layer for sentiment analysis compared to integer encoding.

