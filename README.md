# Linear-regression
Linear Regression and SGD Optimizer on boston house price prediction Data Set

Linear Regression is the techinique which finds a plain, best fits the data such a way that it minimizes squared_loss .
As the name suggest it is a regression problem.
Implimented SGD optimizer on own and compared the error what sklearn inbuilt SGD optimizer gives vs the SGD optimizer build on my own.
you can see the SGD built on my own have loss less than the sklearns inbuilt SGD's loss.

Even here we can add regulizer L1 or L2 
L1 - Manhattan distance >> https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Lasso.html

L2 - Euclidean distance >> https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Ridge.html
so if it has a regulizer obivesly it will have a hyperparamater which give weight to regulizer.
the hyper paramater here is alpha:
* alpha low - model overfits 
* alpha high - model underfits

# Facing error while loading IPYNB "Sorry, something went wrong. Reload?"

please click the following link 
https://nbviewer.jupyter.org/github/prassena/Linear-regression/blob/master/Linear%20Regression%20%26%20Batch%20SGD%20.ipynb
