---
title: "Fake News Detection using Deep Learning"
excerpt: "Implemented a transformer and a RNN model to detect fake news in news articles<br/><img src='/images/bert-accuracy.png' width='80%'>"
collection: projects
---
Work done with Ekimetrics. The report, in French, can be found [here](https://thomasloux.github.io/files/fake-news-detection.pdf).

In a team of 4, we train several models to detect fake news on the dataset 'LIAR' :
- Ensemble Model using 9 Machine Learning algorithms (Decision Tree, Logistic Regression, XGBoost, Random Forest, Extra Trees, AdaBoost, Support Vector Machine with SGD or Linear Programming fitting and Naive Bayes)
- LSTM model and CNN with Word2Vec embeddings. This allows to use effective pretrained embeddings to capture the meaning of the words in the text. The LSTM model then provides a text embedding that is used to classify the article, by using the word embeddings while using the order of the words.
- BERT model using the Transformer architecture for a effective model, which allows to capture the context of the words in the text and interactions between the words thanks to the attention mechanism. Bert achievs a 70% accuracy on the test set.

<img src='/images/bert-accuracy.png' width='80%'>