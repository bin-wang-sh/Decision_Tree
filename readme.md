# Decision Tree  
*it is the exercise for Udacity Data Science course*  
 you'll be given the following sample dataset, and your goal is to define a model that gives 100% accuracy on it.

 The data file can be found under the "data.csv" tab in the quiz below. It includes three columns, the first 2 comprising of the coordinates of the points, and the third one of the label.

The data will be loaded for you, and split into features X and labels y.

You'll need to complete each of the following steps:
1. Build a decision tree model

Create a decision tree classification model using scikit-learn's DecisionTree and assign it to the variablemodel.
2. Fit the model to the data

You won't need to specify any of the hyperparameters, since the default ones will fit the data with an accuracy of 100% in the dataset. However, we encourage you to play with hyperparameters such as max_depth and min_samples_leaf, and try to find the simplest possible model, i.e., the least likely one to overfit!
3. Predict using the model

Predict the labels for the training set, and assign this list to the variable y_pred.
4. Calculate the accuracy of the model

For this, use the function sklearn function accuracy_score.
When you hit Test Run, you'll be able to see the boundary region of your model, which will help you tune the correct parameters, in case you need them.

Note: This quiz requires you to find an accuracy of 100% on the training set. Of course, this screams overfitting! If you pick very large values for your parameters, you will fit the training set very well, but it may not be the best model. Try to find the smallest possible parameters that do the job, which has less chance of overfitting, although this part won't be graded.
