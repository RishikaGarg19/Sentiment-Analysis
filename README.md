# Sentiment-Analysis
This repository contains my first few projects (quite basic) from when I started out with Natural Language Processing in 2020. 
It has 3 files:
## 1. NLP_Proj - My first ever NLP-based project. It uses Bi-LSTM to train a model on text reviews and ratings from Amazon and then classify them as positive (1) or negative (0) based on the new reviews received.
## 2. Twitter Sentiment - This project uses Simple RNN to train a model on Twitter posts (tweets) and then classify new ones as positive (4), neutral (2), or negative (0).
## 3. Sentiment Analysis Twitter Glove - This is an improved version of (2.) in that it uses Bi-LSTM instead of Simple RNN and uses word vectors (GloVe), thereby having better accuracy due to there being better correlation among words, meaning better understanding of context.
The dataset for (1.) is available on Kaggle at https://www.kaggle.com/datasets/datafiniti/consumer-reviews-of-amazon-products.
The dataset for (2.) and (3.) is available on Kaggle at https://www.kaggle.com/datasets/kazanova/sentiment140.
For (3.), the pre-trained vectors (GloVe) are also available on Kaggle at https://www.kaggle.com/datasets/rtatman/glove-global-vectors-for-word-representation.
