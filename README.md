# AutoEncoder
AutoEncoder Recostruction of Mixed MNIST and CIFAR-10 images.
Initially, a rondom image is selected from each of the datasets, then the mean of two images are computed. Moreover, the MNIST images must be pre-processed to match the dimensions of CIFAR-10 ones.
Subsequently, an autoencoder is implemented using pytorch, which takes the mean image as the input and outputs two images, one belonging to CIFAR-10 and the other to MNIST. This way, the reconstruction that we  wanted is obtained.

