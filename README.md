## Fasion MNIST classification and hyperparameter optimization using Scikit-Optmizer

Here we will be concerned with optimizing hyperparameters for a Convolutional Neural Network to get better results in the task of recognizing images from a data set. We will try to find the best ( or at least good) values for 3 parameters, The learning rate for the Adam optmizer, the numer of dense layers and the number of neurons in each dense layer. To find the best values for the 3 parameters, we have some options, we could try all combinations of parameters, wich is an option, but not a good one, if we were to try 10 different values for each parameter, eu would have to make 1000 model evaluations and it could take too much time, this is called grid search. We could also try random values for some time and then save the best set, and well, it does not sound promising, does it?

In the notebook we talk a little about Bayesian optimization using Gaussian Processes and then use gp_minimize from the Scikit-Optmizer to optimize the hyperparameters of an CNN for a classification task

see FashionMNIST_paramOpt.ipynb
