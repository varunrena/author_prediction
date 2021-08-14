# author_prediction
The goal of the problem statement is to determine the authorship of Frankenstein among Authors. The Problem statement was developed to Justify the Author with the help of Data Mining Techniques. They are:

1) RandomForestClassifier Model

2) Logistic Regression Model

3) Bagging Classifier

The data has been collected from Project gutenberg website. We have collected the data of the books from four authors mentioned in the problem statement and three contemporary authors who are in the same genre.Then chunked the large text from the authors book using tokenize from nltk library.

Features : The data I collected consists of two features namely Text, Author.

Author: This Features Holds the Name of the Author which is our class Variable

Text: Text feature holds the string of information which is a line from paragraph obtained from the books
