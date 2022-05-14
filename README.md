# CS294-082-Final-Project
Author: Parth Baokar, Leonard Milea, Yu-Han Pang
## Dataset Discription
The machine learner aims to predict whether a given chest X-ray image is that of normal lungs or that of lungs with pneumonia.

There is 4976 images in our dataset where each image is 64*64. We have a validation set of 16 images and a test set of 624 images.

We have a two-fold metric for success that require measuring accuracy on the provided test set. First, the model should perform at least better than the random guessing accuracy, which can be calculated by 1 / (number of classes) = ½. Moreover, we should also be better than just predicting the most common class (pneumonia) >62.5%.

## MEC Calculation
We calculate the dataset MEC using brainome and analyze the result of brainome's output.

## Training the Machine Learner
We train the machine learner for memorization and generalization.
We use Neural Network model and tried different effort and dataset split. We then plot the training and validation accuracies relative to model MECs.
