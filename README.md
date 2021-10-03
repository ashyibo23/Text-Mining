# Covid-19 Text Mining
Text Mining NLP
This part uses the Coronavirus Tweets NLP data set from Kaggle https://www.kaggle.com/
datatattle/covid-19-nlp-text-classification to predict the sentiment of Tweets relevant to
Covid. The data set (Corona NLP test.csv file) contains 6 attributes:

Colons can be used to align columns.

| Attribute     | Description  |
| ------------- |:-------------:| 
| UserName      | Anonymized attribute. | 
| ScreenName    | Anonymized attribute. |  
| Location | Location of the person having made the tweet.|  
| TweetAt       | Date. | 
| OriginalTweet | Textual content of the tweet. | 
| Sentiment      | Emotion of the tweet. | 


The tasks are divided into several steps:

- Compute the possible sentiments that a tweet may have, the second most popular
sentiment in the tweets, and the date with the greatest number of extremely positive tweets.
Next, convert the messages to lower case, replace non-alphabetical characters with whitespaces
and ensure that the words of a message are separated by a single whitespace.
- Tokenize the tweets (i.e. convert each into a list of words), count the total number
of all words (including repetitions), the number of all distinct words and the 10 most frequent
words in the corpus. Remove stop words, words with <=2 characters and recalculate the number
of all words (including repetitions) and the 10 most frequent words in the modified corpus.
-This task can be done individually from the previous three. Produce a Multinomial
Naive Bayes classifier for the Coronavirus Tweets NLP data set using scikit-learn. For this, store
the corpus in a numpy array, produce a sparse representation of the term-document matrix with
a CountVectorizer and build the model using this term-document matrix. What is the error rate
of the classifier? You may want to check the scikit-learn documentation for performing this task.
 
            

