# NN_MNIST_Dataset
Basic exploration of MNIST and Fashion MNIST using NN classifier a method to decrease classfier's uncertainty. <br>
This exercise is part of a DL course. it provides intial exploration of the NN archetucure using Keras and Tensorflow.<br>
In this excersize:<br>
1. Running Fashion MNIST : https://www.tensorflow.org/tutorials/keras/classification <br>
2. Converting Fashion MNIST recognize digits (original digit MNIST dataset).<br>
3. Plotting a histogram of the accuracies of the test examples for correctly and incorrectly classified objects.<br>
4. Making basic modifications to the networks and reporting the train and test accuracies of each change.<br>
5. Changing the test images and using the other test set. Examining the question: how sure are the classifiers when run on the wrong type of data? <br>
6. Given a test image for one digit and a test image for another digit, generating a set of images.<br>
I(alpha) = alpha * I1 + (1-alpha) * I2 for 100 alphas between 0 and 1. Running the digit classifier on these images and plotting <br>
the results both the classification and the probability of the class. reporting conclusions.<br>
7. Applying a post-training dropout in order to improve the classifier capability to identify when it had made a classification mistake.<br>
