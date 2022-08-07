# Cryptocurrencies
Unsupervised Learning

# Overview

This project will be using machine learning models, pandas libraries to make the data set more ideal to fit with the models, and applying clustering to visualized the best option in crytocurrencies information.

# Purpose

In this challenge we have a data set containig information about cryptocurrencies, and how we don´t know the exactly information we are looking for, it is determined that using unsupervised learning is a good idea, also as the data set provided is not well  given, the data needs to be processed to fit with machine learning models, and finally to group it in clusters to visualized the corresponding findings.


# Summary

To start with, I could say that pandas still being a very useful tool to clean and filter the data, after applying the get.dummies function it is very interestig how the StandardScaler() method convert data to values, then using PCA to reduce dimension of the previous array to the number of components we want, it is well know that this reduction is about a mathematical method, but it s reduced when we use PCA method.

We got a visualization with Elbow curve, which help us to have an idea the number of K values to choose. We can see it determines 3 clusters, however the challege requested to choose 4 cluster while applying the K-Means algorithn, the predictions for this 4 clusters retrieved 532 raws and 9 columns. Finally we visualize the principal components using 3D scatter plot, to see the 4 clusters (PC's) grouped in their corresponding class(0,1 ,2, 3).
