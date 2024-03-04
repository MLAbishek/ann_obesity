I have build a Multi classification artificial neural network model which classifies type of obesity based on some medicinal scientific parameters.

I learned that we have to use "SoftMax" activation function at the output layer of our Ann and should use sparse_categorical_crossentropy as a loss function while compiling our Ann. Then we would get probability of each classes in a list then index of  highest probability of a class among classes  is obtained through np.argmax() from this list. Then that index is used to obtain the classes from our dependent variable column of our parent dataset.

I got accuracy score of 86%

please try my model and suggest any corrections.
