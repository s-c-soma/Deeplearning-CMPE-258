

# Assignment 4 - MNIST classifier with various training knobs with numpy and keras

This folder contains all the 7 assignments of part a, b, and c including the extra credit 3D plot

## Part-a:
1. Assignment_3_Part_A_Numpy
## Part-b:
2. Assignment_3_Part_B.1_Pytorch(without auto differentiation)
3. Assignment_3_Part_B.2_Pytorch(with auto differentiation)
4. Assignment_3_Part_B.3_Pytorch(with linear modules)
## Extra Credit:



############################################################################################################
Part 1:

The assignment is to implement MNIST classifier fully with all the things learnt in last class with many features in numpy in a colab (executed colab should be checked in github and github directory with all resources should be provided)

 

Check Grokking deep learning book 

Sample code :  https://github.com/iamtrask/Grokking-Deep-Learning (Links to an external site.) chapter 7,8,9.  - use mini batch, dropout, learning rate etc.,. 

The code should be very well documented in colab with appropriate sections and should be clean and easy to understand (points will be taken away if the code is not properly commented in colab). 

NOTE: this is individual assignment. we will check if two students are giving identical homework with turnitin as well as global check of copy paste as well. Please ensure you do this homework from scratch and not copy paste. 

a) The code should do mini batch gradient descent along with appropriate learning rate

pick appropriate batch size for minibatch (read fastai and other tips and https://www.kaggle.com/yassineghouzam/introduction-to-cnn-keras-0-997-top-6 (Links to an external site.) for example.) see sample https://machinelearningmastery.com/handwritten-digit-recognition-using-convolutional-neural-networks-python-keras/ (Links to an external site.) as well.

b) The code should do dropout - try various dropout rates and pick the one which works well. (need not be same for all layers ;-) ). - see https://www.kaggle.com/yassineghouzam/introduction-to-cnn-keras-0-997-top-6 (Links to an external site.) for ideas.

The code should initialize the random weights of network properly - see https://docs.google.com/presentation/d/1cYzq7TEGXRAhKF9P0eOI_q01kQAOajl-eS9h3CTGRLg/edit#slide=id.g60fb2717a6_37_196 (Links to an external site.) for more information on how to initialize the random weights before training

c) The code should do basic image augmentations to supplement the training data (not testing data) using keras libraries  (NEW than the deck) - see the image augmentations tried in https://www.kaggle.com/yassineghouzam/introduction-to-cnn-keras-0-997-top-6 (Links to an external site.)

 

d) The code should use  3 or more layers for training (not 2 as in example ) - you have to tune and pick number of neurons in your layer and number of layers

e) The code will continue to use relu activation layer in right places like python code

f) The code should normalize the input as discussed in the class before training (scaling the input)

g) The code should use appropriate learning rate (try out few to find out which one works) - you can use adaptive learning rates like different learning rates per epoch or per mini batch -

see discussion of learning rate schedules https://www.kaggle.com/yassineghouzam/introduction-to-cnn-keras-0-997-top-6 (Links to an external site.) 

https://machinelearningmastery.com/understand-the-dynamics-of-learning-rate-on-deep-learning-neural-networks/ (Links to an external site.)

for more information on different learning rates generations for various epochs etc.,.

h) The code should provide appropriate metrics, visualization,  testing and training accuracy etc.,. and plot the results and confusion matrix  (this is important)

i) The code should display top common errors like in below link.

 

Extra points if you hit 99% test accuracy with these changes (very challenging given you are not using CNNs).

 

Sample (these are with using keras you should try not to use keras for training model /testing other than data preprocessing - like image data augmentation, scaling, normalization ) :

 

https://stats.stackexchange.com/questions/376312/mnist-digit-recognition-what-is-the-best-we-can-get-with-a-fully-connected-nn-o (Links to an external site.)

 

 (Links to an external site.)https://www.kaggle.com/fchollet/simple-deep-mlp-with-keras/code (Links to an external site.) (Links to an external site.)

https://www.kaggle.com/yassineghouzam/introduction-to-cnn-keras-0-997-top-6.  (Links to an external site.)

https://www.kaggle.com/c/digit-recognizer/discussion/61480 (Links to an external site.)

https://www.kaggle.com/adityaecdrid/mnist-with-keras-for-beginners-99457 (Links to an external site.)

 

more inspiration : https://www.kaggle.com/c/digit-recognizer/notebooks (Links to an external site.). (note that most use cnn which we have not yet studied - you should use regular neural network)

 

Your goal is to use plain feed forward NNs without keras NN library but just numpy  (you can use keras only for image augmentation and getting training set and nothing else)

 

Hint: you can hack  on getting these tunings and  hyperparameters by running experiments on gpu using free  automl online services (like https://www.simonwenkel.com/2018/08/30/autokeras_mnist.html (Links to an external site.), or a ton of tools similar to this (like online free https://www.r-bloggers.com/kannada-mnist-prediction-classification-using-h2o-automl-in-r/ (Links to an external site.).  http://docs.h2o.ai/h2o/latest-stable/h2o-docs/automl.html (Links to an external site.).  https://www.h2o.ai/blog/a-deep-dive-into-h2os-automl/?gclid=Cj0KCQiA4sjyBRC5ARIsAEHsELEeWwIWhvZeJj75IRd_PWUBFSEZS7zllR0Abk0Pp9ao7euEmvXzA5IaAnZBEALw_wcB (Links to an external site.). )  - aka - test the right dnn configuration (without cnn) - first or capture from your research online - and then try it out in your python code)

 

Part 2:

 

Do the same using keras and all the knobs on keras (much simpler)

 
 
