# Deep-Convolution-GAN
Implementation of DCGAN for the generation of flowers using the Oxford-102 flower dataset consisting of 102 categories of flower. The categories are merged and shuffled due to less images of all the flower categories.

The generated images are of dimensions 128x128x3 (RGB) while the original images were resized to the same dimensions for training. 

Below are the results after training the model on the dataset and after 1700 epochs(nearly 7-8 hours) on google colab. Training for more epochs could have resulted in better results but due to limited computation capability, the training stopped.

![flower](https://github.com/Akhilesh64/Florum-Ipsum-DCGAN/blob/master/GAN(final).gif)

![new](https://github.com/Akhilesh64/Florum-Ipsum-DCGAN/blob/master/movie.gif)

The model can be furthur fine tuned which I am working on currently, but the process is difficult as GAN's are hard to train.
