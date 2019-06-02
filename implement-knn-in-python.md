# Implement k-nearest neighbours with Python

## Challenge

Implement k-Nearest Neighbours in Python using numpy. We let ourselves using pandas, matplotlib and jupyter notebook for experiments and visualization.

## Homework

To avoid wasting time on the event, we ask you to make some preparatory work before.

* Install Python on your laptop if it’s not installed. For data sciences it’s probably better to install [Anaconda distribution](https://www.anaconda.com/distribution/), choose Python 3.7 version.
* Install a code editor or an IDE. We recommend [Sublime Text](http://www.sublimetext.com), [Visual Studio Code] (https://code.visualstudio.com) or [PyCharm Community](https://www.jetbrains.com/pycharm/).
* Read about k-NN algorithm on [Wikipedia](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm)
* Read the [tutorial on implementing k-NN from scratch](https://machinelearningmastery.com/tutorial-to-implement-k-nearest-neighbors-in-python-from-scratch/). We’ll mostly follow this tutorial, except that we let ourselves to cut corners using pandas to read CSV and using numpy to perform vector operations.

## On site

The goal is to familiarize ourselves with k-NN for classification, and more generally, by scientific environment of Python by implementing the algorithm ourselves and testing it on infamous Iris dataset.

We start at 10am, and we reserve last 20-30 minutes of PyCoffee to discuss the results of the work. Porto i/o provides free coffee to energize you. 

We will start by recapping how k-NN works. Then we split  ourselves into smaller teams and start working on a task.

## Plan of Work

* Download Iris dataset, explore it, and visualize dependency of the iris species from the petal width and length.
* Implement k-NN prediction function using a [tutorial from machinelearningmastery.com](https://machinelearningmastery.com/tutorial-to-implement-k-nearest-neighbors-in-python-from-scratch/) to help yourself. Optional, but recommended: accompany your code with unit tests.
* Split the dataset into a test and train dataset and assess the accuracy of your implementation.

## Extra Challenge

If you happen to have some time left, apply your knowledge to [StackOverflow developers survey](https://insights.stackoverflow.com/survey). Using age and salary fields try to predict if developer is Python or Java developer. Make sure that both features are properly normalized and none of classes is domineering due to its large number to avoid skewing the results. 
