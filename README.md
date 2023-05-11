# Iris-Softmax-Regression

Implementation of Softmax regression on Iris data


Today, there are several machine learning models. Different types of models, like different people, have their own specialties and areas in which they excel more than others. Here in this paper we are going to use logistic regression model services in iris data set to predict flower species. Logistic regression is used to predict a dependent variable, given a set of independent variables, such that the dependent variable is classified. The Logistic function is an S-shaped curve that can take any real-valued number and map it to a value between 0 and 1.

Lily of the valley
It contains three types of irises with 50 examples as well as some properties about each flower. One species of flower can be linearly separated from two other species, but the other two species cannot be separated from each other linearly.
 

The columns of this data set are:

ID = ID,
Sepal length cm = SepalLengthCm,
Sepal Width cm = SepalWidthCm,
Petal length cm = PetalLengthCm,
Petal Width cm = PetalWidthCm,
Species = Species,

The purpose of this work is to identify different types of iris based on the length and width of the sepals and the length and width of their petals.
For this, we first import the desired libraries.
This code uses the softmax function to calculate the softmax activation function.
Defines the one_hot_encoding function for one-hot encoding of tags, and the load_iris_data function for loading the iris dataset.
  The train_softmax function trains the model using a simple gradient descent algorithm, and the test_softmax function tests the model on test data.
The iris dataset is split into training and test sets using the train_test_split function of scikit-learn.
Finally, we call the functions to see the result.


END
