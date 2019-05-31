# Spam_classifier
This is a project based on dataset from UCI machine learning repository.
The dataset provide us the labels/categories (spam/ham) followed by the content of the messages.

First of all i have converted this dataset into a pandas dataframe labelling the data as "status" and "message".
After that i have preprocessed the data using PorterStemmer and removing all the names from the text.
then splitting the dataset into training data and testing data.
the last preprocessing step was vectorizing and i use TfidfVectorizer to do so.

after that the training and testing data is given to the algorithms to train and text themselve.
I have used the following algorithms to train and test data:

Naive Bayes with 97% accuracy
Support Vector Machine with 100% accuracu (I dont know how)
logistics Regression with 96% accuracy
Decision tree with 96% accuracy
