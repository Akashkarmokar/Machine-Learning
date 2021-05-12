The k-NN algorithm is arguably the simplest machine learning algorithm. Building the model consists of storing the training dataset. To make a prediction for a new data, the algorithm finds the closest data point in the training dataset- its "nearest neighborrs".

# k-Neighbors Classification
In its simplest version, the k-NN algorithm only considers exactly one nearest neighbor, which is the  closest training data point to the point we want to make a prediction for. The prediction is then simply the known output for this training point.

Instead of considering only the closest neighbor, we can also consider an arbitrary number k of neighbors.This is where the name of the k-nearest neighbors algorithm comes from. When considering more than one neighbor, we use voting to assign a lebel.This means for binary classification problem for each test point, we count how many neighbor belong to class 0 and how many neighbor belong to class 1. We then assign the class that is more frequent: in other words, the majority class among the k-nearest neighbors.This method can be applied to datasets with any number of classes.

Now let's look at how we can apply the k-nearest neighbors algorithm using scikit-learn.First,we split out data into a training and test set so wen can evaluate generalization performance.
see the -->>     k-NN with two-class classification dataset (forge dataset) file in the above.