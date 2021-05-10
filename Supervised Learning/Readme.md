Supervised learning is used whenever we want to predict a certain outcome from a given input, and  we have examples of input/output pairs. Our Goal is to make accurate predictions for new, never-before-seen data. 
# Classification and Regression 
There are two major types of supervised machine learning problems, called classification and regression.
In classification, the goal is to predict a class label,which is a choice from a predefined list of possibilities. Classification is sometimes separated into binray classification, which is the special case of distinguishing between exactly two classes and multiclass classification, which is classification more than two class.You can thinkof binray classification as trying to answer a yes/no question. Classifying email as either spam or not spam is an example of a binary classification problem.

In Regression, our output will be real number. 
The goal is to predict a continuous number, or a floating-point number in programming terms(or real number in mathmatical term). Predicting a person's annual income from their education, their age, and where they live is an example of a regression problem.


# Generalization, Overfitting and Underfitting
In supervised learning, we want to build a model on the training data and then be able to make accurate predictions on new, unseen that has the same characteristics as the training set we used. If a model is able to make accurate predictions on unseen data, we say it is able to *generalize from the training set to the test set. And oviously we want to build a model that is able to generalize as accurate as possible.

Overfitting occurs when you fit a model too closely to the particularities of the training set and obtain a model that works well on the training set but it is not able to generalize to new data.

Underfitting is opposite of overfitting.

There is a sweet spot in between that will yield the best generalization performance.This is the model we want to find.

# Relation of model complexity to dataset size

It is important to note that model complextity is intimately tied to the variation of inputs contained in your training dataset: the larger variety of data points your data set contains, the more complex a model you can use WITHOUT overfitting. Usually, collecting more data points yield more variety, so larger datasets allow building more complex models.
However, simply duplicating the same data points or collecting very similar data will not help.

Having more data and building appropriately more complex models can often work wonders for supervised learning task.

* NEVER underestimate the power of more data.


