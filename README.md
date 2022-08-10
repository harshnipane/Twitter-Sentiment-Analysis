# Twitter-Sentiment-Analysis
Interpretation and Classification of emotions (Positive, Negative) within text data of twitter using Machine Learning and NLP
## Aim 
Classify the tweets by implementing NLP approach for Sentiment analysis on the provided dataset. The objective is to recognize whether the given tweet is oriented as negative (0) or positive (1)
## Approach
- Download or otherwise retrieve the data.
- Text Preprocessing.
- Verctorization using TfidfVectorizer.
- Train the data using RandomForestClassifier.
- Test the trained model. 

In NLP, text preprocessing is the first step in the process of building a model. This include removing punctuations, removing URL and Stop words, Lower casing, Tokenization, Lemmatization.

For Text Vectorization here we use TFIDF, it stands for ‘term-frequency-Inverse-document-frequency’. Unlike the bag-of-words (BOW) feature extraction technique, we don’t just consider term frequencies in determining TFIDF features. But we also consider ‘inverse document frequency‘ in addition to that.

To Train the model we use RandomForestClassifier. RF  classifier can be described as the collection of tree-structured classifiers. It is an advanced version of Bagging such that randomness is added to it. Instead of splitting each node using the best split among all variables, RF splits each node using the best among a subset of predictors randomly chosen at that node.  

