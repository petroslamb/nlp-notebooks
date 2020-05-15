# Notebooks and other problems I liked


I have been digging into the field of NLP for the last couple of years, by sitting in the weekly meetups of a [local research group](http://nlp.cs.aueb.gr/), gettting into a [local competition](https://race.nbg.gr/challenge-details/wordembedding) and attending a [local summer school](https://www.youtube.com/playlist?list=PLSWgH7JB2-1G2h8wj-ecK8FfpX72Z80_B). 

All this local stuff has now moved in the digital realm, with COVID-19. So I tried to keep up by attending the NLP track for [online ICLR 2020](https://iclr.cc/virtual/index.html), and it was well worth it!

Here, I placed a couple of notebooks on problems I liked.


## Twitter Sentiment Analysis

The [first notebook](./Twitter_sentiment_analysis.ipynb) is a plain old tweet sentiment analysis on a large enough dataset. The solution is not even my own, I took it and worked on it from a notebook shared in Kaggle by [Paolo Ripamonti](https://twitter.com/ripamonti93). My contribution is on enabling the TPU's and providing comments or small suggestions.

I found the solution elegant for the given dataset, which was [Sentiment140](https://www.kaggle.com/kazanova/sentiment140). Paolo took advantage of the size of the dataset (1.6 million labeled tweets) and showcased the power of Word2Vec embeddings trained entirely on it. He proved then that when the embeddings are coupled with an LSTM and supervised training, we are off to a good start :)


## Alzheimer's text classification

The [second notebook](Alzheimer's_text_classification.ipynb) is 
