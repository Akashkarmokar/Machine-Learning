The k-NN algorithm is arguably the simplest machine learning algorithm. Building the model consists of storing the training dataset. To make a prediction for a new data, the algorithm finds the closest data point in the training dataset- its "nearest neighborrs".

# k-Neighbors Classification
In its simplest version, the k-NN algorithm only considers exactly one nearest neighbor, which is the  closest training data point to the point we want to make a prediction for. The prediction is then simply the known output for this training point.

Instead of considering only the closest neighbor, we can also consider an arbitrary number k of neighbors.This is where the name of the k-nearest neighbors algorithm comes from. When considering more than one neighbor, we use voting to assign a lebel.This means for binary classification problem for each test point, we count how many neighbor belong to class 0 and how many neighbor belong to class 1. We then assign the class that is more frequent: in other words, the majority class among the k-nearest neighbors.This method can be applied to datasets with any number of classes.

Now let's look at how we can apply the k-nearest neighbors algorithm using scikit-learn.First,we split out data into a training and test set so wen can evaluate generalization performance.
see the -->>     k-NN with two-class classification dataset (forge dataset) file in the above.




# K-Neighbors Regression

There are also a regression variant of the k-nearest algorithm. Again, let's start by using the single nearest neighbor, this time using the
wave dataset. We've added the test data points as green stars on the x-axis.The prediction using a single neighbor is just the target value of
the nearest neighbor.There are shown as blue stars.

Again, we can use more than the single closest neighbor neighbor for regression.
* when using multiple nearest neighbors, the prediction is the average, or mean, of the relevant neighbors.


The K-nearest neighbors algorithm for regression is implemented in the kNeighborsRegressor class in Scikit-learn. It's used similarly to Kneighbors classifier.

You can find code here -> https://github.com/Akashkarmokar/Machine-Learning/blob/main/Supervised%20Learning/K-Nearest%20Neighbors/K-neighbors%20regression.ipynb


