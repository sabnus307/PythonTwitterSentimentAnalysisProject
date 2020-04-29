# PythonTwitterSentimentAnalysisProject
Final Project of the course Python Functions, Files, and Dictionaries. This course is part of the Python 3 Programming Specialization offer by University of Michigan in Coursera. You can find more information at https://www.coursera.org/learn/python-functions-files-dictionaries/
## About it
We have provided some synthetic (fake, semi-randomly generated) twitter data in a csv file named project_twitter_data.csv which has the text of a tweet, the number of retweets of that tweet, and the number of replies to that tweet. We have also words that express positive sentiment and negative sentiment, in the files positive_words.txt and negative_words.txt.

Your task is to build a sentiment classifier, which will detect how positive or negative each tweet is. You will create a csv file, which contains columns for the Number of Retweets, Number of Replies, Positive Score (which is how many happy words are in the tweet), Negative Score (which is how many angry words are in the tweet), and the Net Score for each tweet. At the end, you upload the csv file to Excel or Google Sheets, and produce a graph of the Net Score vs Number of Retweets.

## functions
#### 1. def strip_punctuation(strWord): 
which takes one parameter, a string which represents a word, and removes characters considered punctuation from everywhere in the word. 
#### 2. def get_pos(strSentences):
which takes one parameter, a string which represents a one or more sentences, and calculates how many words in the string are considered positive words. Use the list, positive_words to determine what words will count as positive. The function should return a positive integer - how many occurances there are of positive words in the text.
#### 3. def get_neg(strSentences):
which takes one parameter, a string which represents a one or more sentences, and calculates how many words in the string are considered negative words. Use the list, negative_words to determine what words will count as negative. The function should return a positive integer - how many occurances there are of negative words in the text.
#### 4. def writeInDataFile(resultingDataFile):
which takes one parameter, a string which represents all data in project_twitter_data.csv, and write a csv file called resulting_data.csv, which contains the Number of Retweets, Number of Replies, Positive Score (which is how many happy words are in the tweet), Negative Score (which is how many angry words are in the tweet), and the Net Score (how positive or negative the text is overall) for each tweet. The file have its headers in that order.
## Scatterplot
< src="![Screenshot (66)](https://user-images.githubusercontent.com/63044349/80573510-e80de500-8a21-11ea-9e0a-2c7832472756.png)  >

## Authors/authors:
Sabbir Rahman. Contact: sabbirrahman@iut_dhaka.edu


Course material: University of Michigan in Coursera. You can find more information at https://www.coursera.org/learn/python-functions-files-dictionaries/
