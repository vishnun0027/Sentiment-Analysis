# Sentiment analysis
Sentiment analysis is a technique used to determine the emotional tone or sentiment expressed in a text. It involves analyzing the 
words and phrases used in the text to identify the underlying sentiment, whether it is positive, negative, or neutral.

There are several ways to perform sentiment analysis on text data, with varying degrees of complexity and accuracy. The most common
methods include a lexicon-based approach, a machine learning (ML) based approach, and a pre-trained transformer-based deep learning approach. Let’s look at each in more detail

## Lexicon-based analysis

This type of analysis, such as the NLTK Vader sentiment analyzer, involves using a set of predefined rules and heuristics to determine the sentiment of a piece of text. These rules
are typically based on lexical and syntactic features of the text, such as the presence of positive or negative words and phrases. [NLTK Sentiment Analysis](https://github.com/vishnun0027/Sentiment-Analysis/blob/master/NLTK%20Sentiment%20Analysis.ipynb)

## Machine learning (ML)

This approach involves training a model to identify the sentiment of a piece of text based on a set of labeled training data. These models can be trained using a wide range of ML algorithms, including decision trees, support vector machines (SVMs), and neural networks.[ML Sentiment Analysis](https://github.com/vishnun0027/Sentiment-Analysis/blob/master/ML%20Sentiment%20Analysis.ipynb)

## Deep learning 

Sentiment analysis using deep learning models involves classifying text data (e.g., reviews, tweets) as positive or negative based on the sentiment expressed. Key models include

*  RNN (Recurrent Neural Networks): These networks capture temporal dependencies in sequential data, making them suitable for analyzing text where context and order of words matter.[RNN](https://github.com/vishnun0027/Sentiment-Analysis/blob/master/DL%20RNN%20Sentiment%20Analysis.ipynb)

* LSTM (Long Short-Term Memory): An advanced type of RNN designed to handle long-term dependencies and overcome issues like vanishing gradients. LSTMs maintain information over long sequences, making them effective for sentiment analysis.[LSTM](https://github.com/vishnun0027/Sentiment-Analysis/blob/master/DL%20LSTM%20Sentiment%20Analysis.ipynb)

* GRU (Gated Recurrent Unit): Similar to LSTMs but with a simpler architecture. GRUs are efficient and perform well on sequential data, balancing model complexity and training time.[GRU](https://github.com/vishnun0027/Sentiment-Analysis/blob/master/DL%20GRU%20Sentiment%20Analysis.ipynb)

## DATASET
**Large Movie Review Dataset** [data](https://ai.stanford.edu/~amaas/data/sentiment/) \
This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. We provide a set of 25,000 highly polar movie reviews for training, and 25,000 for testing
