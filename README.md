# Machine-Learning-Octave
My Machine Learning Course using Octave for ML algorithms.

different exercise are done see the details here to get to know what happen in each one:

## Ex1: Linear Regression
ex1.m file: implemented linear regression with one variable to predict profits for a food truck. Suppose you are the CEO of a
restaurant franchise and are considering different cities for opening a new outlet. The chain already has trucks in various cities and you have data for profits and populations from the cities.You would like to use this data to help you select which city to expandto next.

ex2 multi.m file: implement linear regression with multiple variables to predict the prices of houses. Suppose you are selling your house and you want to know what a good market price would be. One way to do this is to first collect information on recent houses sold and make a model of housing prices.

## Ex2:  Logistic Regression

ex2.m : build a logistic regression model to predict whether a student gets admitted into a university. 

ex2 reg.m : implemented regularized logistic regression to predict whether microchips from a fabrication plant passes quality assurance (QA). During QA, each microchip goes through various tests to ensure it is functioning correctly. Suppose you are the product manager of the factory and you have the test results for some microchips on two different tests. From these two tests, you would like to determine whether the microchips should be accepted or rejected. To help you make the decision, you have a dataset of test results on past microchips, from which you can build a logistic regression model. You will use another script, ex2 reg.m to complete this portion of the exercise.

## Ex3: Logistic Regression and Neural Networks

ex3.m :  Used logistic regression and neural networks to recognize handwritten digits (from 0 to 9). 

ex3_nn.m: Implemented a neural network to recognize handwritten digits 

## Ex4: Neural Networks
Neural Networks: ex4.m
I implemented the backpropagation algorithm to learn the parameters for the neural network to predict handwritten digits with the learned parameters.

Backpropagation: nnCostFunction.m
I implemented the backpropagation algorithm to compute the gradient for the neural network cost function.

## Ex5: Regularized Linear Regression and Bias v.s. Variance

ex5.m: I implement regularized linear regression to predict the amount of water flowing out of a dam using the change of water level in a reservoir.

Bias-variance:
An important concept in machine learning is the bias-variance tradeoff. Models with high bias are not complex enough for the data and tend to underfit, while models with high variance overfit to the training data.I plot training and test errors on a learning curve to diagnose bias-variance problems.

Polynomial regression:
The problem with our linear model was that it was too simple for the data and resulted in underfitting (high bias). In this part of the exercise, I address this problem by adding more features.

## Ex6: Support Vector Machines

 I used support vector machines (SVMs) to build a spam classifier for Emails. ex6.m is about the fundamental concepts in SVM and in ex6_spam I implemented the Spam Classifier.
 
## Ex7: Unsupervised Learning: K-means Clustering and Principal Component Analysis

ex7.m : Implemented the K-means clustering algorithm and apply it to compress an image. 
ex7 pca.m: Used principal component analysis (PCA) to perform dimensionality reduction and the used it on a dataset of 5000 face image dataset.

## Ex8: Anomaly Detection and Recommender Systems

I implement the anomaly detection algorithm and apply it to detect failing servers on a network.  The features measure the throughput (mb/s) and latency (ms) of response of each server.
In the second part, I use collaborative filtering to build a recommender system for movies.This dataset consists of ratings on a scale of 1 to 5. The dataset has nu = 943 users, and nm = 1682 movies. 
