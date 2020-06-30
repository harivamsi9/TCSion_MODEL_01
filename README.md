# TCSion_MODEL_01
The amount of data that is produced in the past decade is much greater than the total of the data produced before that from the time of invention of the computer or the internet. Each day, trillions of terabytes of data is being produced and consumed. And in the online retail reviews, or even our particular case of interest i.e. online movie reviews sentiment analysis. There are so many ways that a reviewers can give a feedback about a movie. And each reviewer based on his interests give different kinds of feedbacks which can be positive, negative, neural, and sometimes extreme.  It’s very hard for someone to monitor such comments, and also it is of importance to know the talk of the each movie for better analytics. And manually performing this task is extremely tedious, and time consuming. Our project focuses on automating this aspect, by performing the sentiment analysis on the movie reviews data so we classify each review as positive, negative, neutral.   We can use this project in various aspects, either as just how it is to know the nature of the review, or this could be a sub module for building the a recommendation system, or personality analyzer. 


### No matter what the application or data set is, the steps to achieve the sentiment analysis are almost the same.

## Pre-process the data, Train the Model, Test the Model, Find the Accuracy
1. combine the texts (text data from pos and neg)
2. visualize them for better understanding
3. Use NLTK library for NLP operations like tokenizing, removing stopwords, etc.
4. remove HTML tags with the help of BeautifulSoup
5. Convert the entire data into string format, and store in a csv file. (Sentiment analysis can be done only on string format)
6. Use NLTK to apply Bag Of Words algorithm, followed by TD-IDF to train and test the data set. (you can hyper tune the parameters and play around with the model and accuracy)
7. apply different types of algorithms to get a good and competitive accuracy.
** You can use various libraries and approaches and still arrive at the same results.
