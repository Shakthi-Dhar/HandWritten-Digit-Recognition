# HandWritten-Digit-Recognition
This is a basic project using deep learning and cv2

Machine learning and deep learning plays an important role in computer technology and artificial intelligence. With the use of deep learning and machine learning, human effort can be reduced in recognizing, learning, predictions and many more areas. This article presents recognizing the handwritten digits (0 to 9) from the famous MNIST dataset, comparing classifiers like KNN, PSVM, NN and convolution neural network on basis of performance, accuracy, time, sensitivity, positive productivity, and specificity with using different parameters with the classifiers.

Handwritten digit recognition has gained so much popularity from the aspiring beginner of machine learning and deep learning to an expert who has been practicing for years. Developing such a system includes a machine to understand and classify the images of handwritten digits as 10 digits (0–9).

Detailed Explantion of how the code works:

# 1st Import all dependencies
# 2nd Load the dataset from tensorflow-mnist
# 3rd We should split the dataset into training and test data
The training set contains a known output and the model learns on this data in order to be generalized to other data later on. We have the test dataset (or subset) in order to test our model’s prediction on this subset.
# 4th Lets create a neural network with 2 inner layers and the output layer shall contain 10 possible outcomes [0-9]
# 5th We train the model and test it on a sample from test dataset
# 6th Now in order to test on real time data we need to access the webcam using cv2, and capture the image and store it as photo.jpg
# 7th Now we need to pass the image to the the trained model to get a predicted output
# 8th Boom, its done. You can now see the predicted values
