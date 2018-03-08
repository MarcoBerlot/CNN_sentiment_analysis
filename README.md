# CNN_sentiment_analysis

## Introduction:
The purpose of this project was to recreate the CNN for NLP model from Kim EMNLP 2014 for Sentiment Analysis. This CNN model was trained on the Stanford Sentiment Treebank dataset. Six different experiments were run and different values of accuracy and performance were analysed for each method.

## How To Run:
The code supports GPU use over CUDA. In order to run it over GPU, uncomment line 275. The code goes over all the six experiments, for each of them it trains the CNN, creates the initial weights from Glove or Word2Vec and then calculate the accuracy over the validation data. Make sure to be in the same folder of the Stanford Sentiment Treebank, the Glove and Word2Vec txt files. They can be downloaded here:

[stanford Sentiment Treebank](http://nlp.stanford.edu/)
[Glove](https://nlp.stanford.edu/projects/glove/)
[Word2Vec](https://github.com/mmihaltz/word2vec-GoogleNews-vectors)
