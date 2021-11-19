# Sarcasm-Detection-ML-DL
News Headlines Dataset For Sarcasm Detection

I have made two notebooks.
The first notebook consists of various Machine Learning models tuned in a pipeline.
The second notebook consists of a BiDirectional LSTM and a transfer learning model where I used the Universal Sentence Encoder for Embeddings.

CREDITS: https://www.kaggle.com/rmisra/news-headlines-dataset-for-sarcasm-detection

RESEARCH PAPER: https://arxiv.org/pdf/1908.07414.pdf

<img src = https://www.storypick.com/wp-content/uploads/2015/08/Chandler-Cover-1024x576.jpg >

Context
Past studies in Sarcasm Detection mostly make use of Twitter datasets collected using hashtag based supervision but such datasets are noisy in terms of labels and language. Furthermore, many tweets are replies to other tweets and detecting sarcasm in these requires the availability of contextual tweets.

To overcome the limitations related to noise in Twitter datasets, this News Headlines dataset for Sarcasm Detection is collected from two news website. TheOnion aims at producing sarcastic versions of current events and we collected all the headlines from News in Brief and News in Photos categories (which are sarcastic). We collect real (and non-sarcastic) news headlines from HuffPost.

This new dataset has following advantages over the existing Twitter datasets:

Since news headlines are written by professionals in a formal manner, there are no spelling mistakes and informal usage. This reduces the sparsity and also increases the chance of finding pre-trained embeddings.

Furthermore, since the sole purpose of TheOnion is to publish sarcastic news, we get high-quality labels with much less noise as compared to Twitter datasets.

Unlike tweets which are replies to other tweets, the news headlines we obtained are self-contained. This would help us in teasing apart the real sarcastic elements.

Content
Each record consists of three attributes:

is_sarcastic: 1 if the record is sarcastic otherwise 0

headline: the headline of the news article

article_link: link to the original news article. Useful in collecting supplementary data

General statistics of data, instructions on how to read the data in python, and basic exploratory analysis could be found at this GitHub repo. A hybrid NN architecture trained on this dataset can be found at this GitHub repo.

Inspiration
Can you identify sarcastic sentences? Can you distinguish between fake news and legitimate news?
