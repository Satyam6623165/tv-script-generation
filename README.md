# Tv-Script-Generation
<hr>
This project is a part of Udacity's Deep Learning Nanodegree.<br>In this project we generate a fake tv script on Seinfeld dataset of 9 seasons. 
## Core Concepts used
**1**. The model is based on RNNs (LSTMs specifically) to figure out patterns between words in sentences and used the topk sampling to predict the new word to introduce some randomness.  
**2**. Used an Embedding layer for dimensionality reduction as one hot encoded word vectors would be too large and compute time can be extremely high. 
