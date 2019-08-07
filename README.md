# Project: Finding Donors for CharityML
# Part of Udacity Data Scientist Nanodegree 


### About

The project aims to evaluate and select the optimal supervised learning algorithm available that is adequate to accurately model individuals' income using data collected from the 1994 U.S. Census. In addition to accurately predicts whether an individual makes more than $50,000. Understanding an individual's income can help a non-profit better understand how large of a donation to request.

Based on the accuracy and f-score and the training time the best model is Random Forest Classifier (RFC).
Since we are dealing with a classfication problem using Random Forest would be optimal and fast and easy to communicate results to the stakeholders.

#### preprocessing
- Transforming Skewed Continuous Features
- Normalizing Numerical Features
- One-hot Encoding
#### Implement performance metrics to evaluate the potential algorithms
#### Choosing the Best Model & Model Tuning




### Install

This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

### Data

The modified census dataset consists of approximately 32,000 data points, with each datapoint having 13 features. This dataset is a modified version of the dataset published in the paper *"Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid",* by Ron Kohavi. You may find this paper [online](https://www.aaai.org/Papers/KDD/1996/KDD96-033.pdf), with the original dataset hosted on [UCI](https://archive.ics.uci.edu/ml/datasets/Census+Income).

