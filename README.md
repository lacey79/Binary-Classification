# Binary-Classification
This program is about building a binary classification model using Keras library. The program starts by installing the necessary libraries (Keras and NumPy), and then imports the required libraries and defines hyperparameters for the deep learning model.

The program uses a simple example of a binary classification problem where the input features are 10-dimensional, and the output is binary (0 or 1). A feedforward neural network with two hidden layers is used, each with 5 units, and the output layer has a single unit with a sigmoid activation function for binary classification.

Next, the program generates some random training data, and then uses the Sequential class from Keras to build the model. The input layer is added first, followed by the hidden layers (the number of hidden layers is defined by the user), and the output layer is added last. The compile() method is used to configure the model with an optimizer and loss function.

Finally, the program trains the model on the training data using the fit() method, and then makes predictions on new data using the predict() method. The predicted values for the test data are then outputted.
