# Super-Resolution-Convolutional Neural-Network



### Prerequisites

This lab is conducted using a python libraries Tensorflow, Matplotlib, numpy, scipy, skimage, pdb, os & time. 

### Installing

I have used environment of Jupyter notebook to run the file.

### Purpose

The purpose of this lab is to implement the concept introduced in the research paper attached in the repo about Super Resolution Convolutional Neural Network(SRCNN) inroducted by Chao Dong and others. 
The concept of SCRNN is that it compares ground truth image with the model's generated image. This is what is done in the code.

### How the purpose is achieved

Ground truth image is created by scaling down and up the original image. First thing to do is to have no remainder while scaling operation. We need to find modulo of height (and width) and scale factor.
Then, subtract the modulo from height (and width) of original image size.
There would be no remainder even after scaling operation.

After this, we run the neural networks and compare the ground truth image with the results generated by neural network. We do it using MSE(Mean Square error)


## Built With

* Queen Mary University of London - Deep Learning Asssignment

