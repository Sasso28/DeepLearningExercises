# DL/MLExercises

In this repository I will add the projects I did as training. They are not directed correlated as my primary goal is to show my abilities working on different type of datasets.

PROJECTS ON CLASSIFICATION

1. _Indians Diabetes_ is a study to predict the appearance of diabetes depending on some numerical variables;
In this project both Machine Learning and Deep Learning have been used in order to compare the results.

a. For the ML part, the first thing is to extract the relevant features;
b.
c.
d.
e. validation


For the DL part after the definition of the model to take the first result, a _function_ has been defined to reproduce multiple times the model. 
In this way the the process required to have a solid result has been authomatized and the average of the _n_ models has been taken as the final accuracy.

a. creation of the Sequential model;

Implementation of a fully-connected network structure with three layers; 
Specify the number of neurons or nodes in the layer as the first argument, and specify the activation function using the activation argument.

b. Dense Class, ensuring the _input layer_ has the right number of input features; there have been used 2 hidden layers
c. Output layer has one node and uses the sigmoid activation function.

2. _Occupancy Detection Data Set_ is a project done to predict if the each house is occupied or not depending on some features.
As in the previous project, I have used both ML and DL techinques to achieve the result.
The goal is to optimize the consumption of energy inside a house.

The project was done in a Jupyter notebook. 
In that enviromment the first two cells of code (excluding the import of the dataset) generated a plot that I can't replicate in GitHub nor in Colab. For the moment.

In the ML part of the notebook:
a. I used different types of scalers for a couple of features. Their value is small enough to require a normalization;
b. After the EDA I add a variable to include the effect of the hour of the day during the analysis;
c. I tried a threes hyper-parameters and I reported the values of their relative accuracy in a plot;
d. I implemented the various hyper-parameters in the two models created; they choise was for th combination that got a more balanced result; the two algorithms choosed are KNeighborsClassifier and SVC


In the DL part of the notebook there are three models:
a. The first one has 2 hidden layers, both with 'relu' activation, and the final layer with 'sigmoid';
b. The second one has a dropout of 0.2 after the first hidden layer; the activation works the same as previously;
c. The third one has implemented the Lasso regularization
d. The last step is to plot the training and the validation loss; the Third model turned out to be the most accurate;


Comparison ML vs DL:
The result from the accuracy are comparable, the final choise has been made for DL because the results look more balanced;
Probably the ML models tend to overfit the data.
PROJECTS ON REGRESSIONS
