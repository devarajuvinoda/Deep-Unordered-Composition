# Deep-Unordered-Composition

A deep unordered model called Deep Averaging Network(DAN) and it works as follows,
  * Take the vector average of the embeddings associated with an input sequence of tokens
  * Pass that average through one or more feedforward layers
  * Perform (linear) classification on the final layer’s representation

Used above approach for text classification on [BBC Dataset](http://mlg.ucd.ie/datasets/bbc.html) and sentiment analysis on [IMDB Dataset](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews). Following are the result,
  * Test accuracy for classification 0.97687
  * Test accuracy for sentiment analysis 0.8878

Reference:
[Deep Unordered Composition Rivals Syntactic Methods for Text Classification](https://people.cs.umass.edu/~miyyer/pubs/2015_acl_dan.pdf)
[Universal Sentence Encoder](https://arxiv.org/pdf/1803.11175.pdf)
