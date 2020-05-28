# Top 10 Algorithms for Binary Classification
#### How to implement the 10 most important binary classification algorithms with a few lines of Python and how they perform

##  Introduction
Binary classification problems can be solved by a variety of machine learning algorithms ranging from Naive Bayes until deep learning networks. Which solution performs the best in terms of runtime and accuracy depends on the data size (number of samples and features) and data quality (outliers, imbalanced data). 
This article provides an overview and code examples you can easy try out yourself. The aim is to get quick first working results with Python. I will not explain each algorithm in detail to keep the article compact. There are many very good article out there which do that much better as I could. I added some references to each algorithm in case you want to understand more about the algorithm and its underlying theory. 
In this article we will focus on top 10 most common binary classification algorithms:
1. Naive Bayes
2. Logistic Regression
3. K-Nearest Neighbours
4. Support Vector Machine
5. Decision Tree 
6. Bagging  Decision Tree (Ensemble Learning I)
7. Boosted Decision Tree (Ensemble Learning II)
8. Random Forest (Ensemble Learning III)
9. Voting Classification (Ensemble Learning IV)
10. Neuronal Network (Deep Learning)

With the aim to keep it as simple as possible we will only use three Python libraries in this tutorial: Numpy, Sklearn and Keras.
In the code examples I always import the necessary library right on top of the the code snipped to make clear that it is used next. You can load them all in the beginning of your script.

## Datasets

In this git folder you find Jupyter Notebooks where I applied the Top 10 binary classification methods on several datasets from differetn areas

1. IMDB Dataset - Natural language processing - binary sentiment analysis 
2. FashionMNIST Dataset - Computer vision - binary image classification 
3. Wisconsin Breast Canser Dataset - simple tabled data - simple binary classification

## Medium Article

Some more details about this learning notebooks can be found in my Medium article 