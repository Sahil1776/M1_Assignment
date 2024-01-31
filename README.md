# M1_Assignment: Text Processing and Edit Distance

Course: Natural Language Processing

- Extracted tweets were collected into a pandas dataframe
- Hyperlinks, hashtags etc were removed using Regex
- NLTK library was used to perform tasks like tokenization, removing stopwords and punctuations
- Words were stemmed using PorterStemmer (from nltk.stem import PorterStemmer)
- A function called preprocess_tweet(tweet) was constructed which was able to do all of this in one go
- A new column called 'preprocessed_tweet' was constructed using this function over all the tweets in the dataframe
- Finally, a function called leven_dist(string1, string2) was constructed which was able to calculate the edit distance between two strings
