The purpose of this project was to implement a simple GAN architecture to experiment with the methodology behind unsupervised learning and generative models.
The GAN was implemented on two classical ML image datasets - the MNIST handwritten digit dataset which consists of only 10 classes corresponding to the 10
digits, and CIFAR10 which contains a high number of diverse classes (ships, planes, types of animals and more). These two datasets were purposefully chosen
to see how the performance of a GAN differs with the complexity of the data it is trained on.
The uploaded PNG files show results after 70 epochs - the generated digits for the MNIST dataset are quite believable, while the generated images for the CIFAR10
dataset resemble animals and objects with respect to color and general layout, but lack any clear detail. Due to limited training resources the model could only
be trained for 70 epochs; performance on the CIFAR10 dataset would likely continue to improve with more training time.

Supplied is the .ipynb used for the implementation of the GAN on each dataset as well as a plot of example generated images from each model.
