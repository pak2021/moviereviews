# moviereviews
Determining if a review is positive or negative by analyzing the vocabulary used using NLP.
Reviews were cleaned by removing stopwords, punctuations etc.Each entry consisted of the collection of useful words in review,, WordNetLemmatizer was used to remove similar meaning words by determining their type(pos_tag).After cleaning CountVectorizer was applied on the dataset to reduce the number of features. SVC() from sklearn.svm was used for the final training and predictions.
