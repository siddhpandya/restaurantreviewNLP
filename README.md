# restaurantreviewNLP
Predict positive or negative reviews of customer
## pre-requisite
* [pandas](https://pandas.pydata.org/)
* [The Natural Language Toolkit](https://www.nltk.org/)
* [sklearn](https://scikit-learn.org/stable/)
## Explaination
* Load dataset(.tsv) using pandas
* Download stopwords and remove it through nltk-(remove words like the,a,an etc..)
* PorterStemmer to simplify the sentences
* CountVectorizer to fit transform the data
* Apply GaussianNB to train the model
