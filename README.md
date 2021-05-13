# DCGAN
Deep Convulational Generarive Adversarial Networks are comparatively stable GAN's while training compared to Normal GAN.

> Architecture guidelines for stable Deep Convolutional GANs

*   > Replace any pooling layers with strided convolutions (discriminator) and fractional-strided convolutions (generator).
*   > Use batchnorm in both the generator and the discriminator.
*   > Remove fully connected hidden layers for deeper architectures.
*   > Use ReLU activation in generator for all layers except for the output, which uses Tanh.
*   > Use LeakyReLU activation in the discriminator for all layers.


In this implementation, DCGAN is trained over MNIST digit Dataset for over 10,000 epochs, after training model tries to generate dataset similar to MNIST, which can be seen at the end. Results are quite satisfactory and visually appealing.




