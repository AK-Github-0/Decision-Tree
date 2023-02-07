# Decision-Tree

This code implements a Decision Tree classifier to predict whether a tennis player will play tennis or not based on the weather conditions. The weather conditions are represented by the features "outlook", "temperature", "humidity", and "wind".

The code first loads the tennis data from the "tennis.txt" file and encodes the categorical variables using the LabelEncoder from the sklearn library. Then, it splits the data into a training set and a test set using the train_test_split function from the sklearn.model_selection library.

The Decision Tree classifier is fit on the training data using the fit method from the sklearn.tree library, and the resulting model is used to plot the tree and print a text representation of the tree.

The exported text representation of the tree provides a readable format of the tree structure, and the conditions at each node that determine the class label.
