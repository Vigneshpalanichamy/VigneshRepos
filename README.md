Text analysis using SVM and random forest classifier 

#Imported libraries 

##Numpy In Python:

Numpy help us to implement numerical computations and functions for working in domain of linear algebra, 
fourier transform, and matrices. 
Numpy stands for Numerical Python and is the core library for Numerical and scientific computations.
This library called as Numpy provides us with multi-dimensional arrays so that we can implement all the numerical tasks.

###Pandas Library In python:

1)Loading and saving data 
2)Column insertion and deletion
3)Data Selection 
4)Column and row renaming 
5)Row deletion
6)Data sorting
7)Handling Missing values
8)Handling Duplicated data 
9)Data Exploration
10)Data Visualization

####Matplotlib Library

Matplotlib is a visualization library in Python for 2D plots of arrays. 
It consists of several plots like line, bar, scatter, histogram etc.
Matplotlib is a multi-platform data visualization library built on NumPy arrays.
One of the advantage of visualization is that it allows us visual access to huge amounts of data in easily digestible visuals.

process notes:

1) imported libraries to work with 
2)read the data set 
3)check the data tables 
4)Check for null values 
5)describe method is used for calculating some statistical data like percentile, mean and std of the numerical values of the Series or DataFrame. It analyzes both numeric and object series and also the DataFrame column sets of mixed data types.
6)Check the data set whether the same is balanced or imbalanced - used labels in column to find values of spam / ham 
7)Separate the details of ham and spam separately 
8)Data concatenation of spam and ham with "ignore_index = True", do not use the index labels.If True, raise ValueError on creating index with duplicates. sort : Sort columns if the columns of self and other .Explicitly pass sort=True to silence the warning and sort.
8)Visualization of data with histogram using length of text , punctuation of text - inference found as not useful 
9)Segregate the data into train and test
10)Feature extraction is done using tfidf vectorizer -  Transforms text to feature vectors that can be used as input to estimator. vocabulary_ Is a dictionary that converts each token (word) to feature index in the matrix, each unique token gets a feature index.In each vector the numbers (weights) represent features tf-idf score
11)Model used is Randomforest classifier - Random forest classifier creates a set of decision trees from randomly selected subset of training set. It then aggregates the votes from different decision trees to decide the final class of the test object.
12)Metrics used for classification :

###If it is binary classification:

    Accuracy
    Log-loss
    Precision for both classes
    Recall for both classes
    F-score

###If it is multi class classification:

    Macro accuracy
    Micro accuracy for all classes
    Precision
    Recall
    F-score

13)2nd model used SVM - Support Vector Machines (SVMs) are widely applied in the field of pattern classifications and nonlinear regressions.SVMs have been transformed tremendously to be used successfully in many real-world problems such as text (and hypertext) categorization, image classification, bioinformatics (Protein classification, Cancer classification), handwritten character recognition, etc.

14) In this case SVM performs better than Random forest classifier
