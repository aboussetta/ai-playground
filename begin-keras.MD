# Keras Overview

### [Develop Your First Neural Network in Python With Keras Step-By-Step, Jason Brownlee](https://machinelearningmastery.com/tutorial-first-neural-network-python-keras/)
  - Primary example: Predicting diabetes sufferers using physiological measures of Pima Indians
  - Provided brief and clear overview of how to use Keras namely:
   - Load and preprocess data
   - Define model
   - Compile model
   - Fit model
   - Evaluate model
   - Make predictions on unseen data

### [Another Keras Tutorial For Neural Network Beginners, David Sheehan](https://dashee87.github.io/data%20science/deep%20learning/python/another-keras-tutorial-for-neural-network-beginners/) (with [Jupyter Notebook](https://github.com/dashee87/blogScripts/blob/master/Jupyter/2017-09-06-another-keras-tutorial-for-neural-network-beginners.ipynb))
 - Criticized aforementioned article by Jason Brownlee above for not mentioning overfitting, and emphasized **overfitting prevention techniques** _(early-stopping, dropouts)_
 - **Best takeaway**:  Use hyper parameter optimization to select model with best performance like [repeated validation (StratifiedKFold for example)](http://scikit-learn.org/stable/modules/generated/sklearn.model_selection.StratifiedKFold.html).
 - Mentioned crucial hyperparameter options namely:   
   - [different initialization techniques](https://keras.io/initializers/)
   - [activation functions](https://stats.stackexchange.com/questions/115258/comprehensive-list-of-activation-functions-in-neural-networks-with-pros-cons)  
   - [optimizers](https://keras.io/optimizers/)
   - [loss functions](https://keras.io/losses/)

### [How to Grid Search Hyperparameters for Deep Learning Models in Python With Keras, Jason Brownlee](https://machinelearningmastery.com/grid-search-hyperparameters-deep-learning-models-python-keras/)

  - Gives an overview of how to use grid search capability from the scikit-learn python machine learning library to tune the hyperparameters of Keras deep learning model
  - Discusses how to tune batch size and training epochs, optimization algorithms, learning rate and momentum, network weight initialization, activation functions, dropout regularization, number of neurons in the hidden layer.


# Videos 
- [Keras Deep-learning Tutorial](https://www.youtube.com/watch?v=Tp3SaRbql4k)
- [Keras Explained, Siraj Raval](https://www.youtube.com/watch?v=j_pJmXJwMLA)


# Other Beginner Short Keras / ML Articles  
- [A simple neural network with Python and Keras, Adrian Rosebrock ](https://www.pyimagesearch.com/2016/09/26/a-simple-neural-network-with-python-and-keras/)
- [Keras Tutorial: The Ultimate Beginner’s Guide to Deep Learning in Python](https://elitedatascience.com/keras-tutorial-deep-learning-in-python)
- [Keras Feedforward Tutorial](https://github.com/Vict0rSch/deep_learning/tree/master/keras/feedforward)
- [Image Classification using Feedforward Neural Network in Keras, Vikas Gupta](https://www.learnopencv.com/image-classification-using-feedforward-neural-network-in-keras/)
- [Beginning Machine Learning in Keras](https://www.raywenderlich.com/181760/beginning-machine-learning-keras-core-ml)
- [Bare bones of neural network](http://www.orbifold.net/default/2016/11/18/bare-bones-of-neural-networks/)
-  [Some feedforward neural networks using Keras	](http://www.orbifold.net/default/2016/11/25/some-feedforward-neural-networks-using-keras/)
- [Fast Forward Labs: Hello world in Keras (Jupyter Notebook)](https://github.com/fastforwardlabs/keras-hello-world/blob/master/kerashelloworld.ipynb)
