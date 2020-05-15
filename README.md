# NLP Notebooks and Other approaches on problems I liked


I have been digging into the field of NLP for the last couple of years, by attending a local meetup and a summerschool. Here, I placed a couple of notebooks on problems I liked and probably a few other things in the future.


## Twitter Sentiment Analysis

The [first notebook](./Twitter_sentiment_analysis.ipynb) is just on plain old tweet sentiment analysis on a large enough dataset. The solution is not even my own, I took it and worked on it from a notebook shared in Kaggle by [Paolo Ripamonti](https://twitter.com/ripamonti93). 

I found the solution elegant for the given dataset, which was [Sentiment140](https://www.kaggle.com/kazanova/sentiment140). Paolo took advantage of the size of the dataset (1.6 million labeled tweets) and showcased the power of Word2Vec embeddings trained entirely on it. 

He proved then that when the embeddings are coupled with an LSTM and supervised training, we are off to a good start :)


## 
