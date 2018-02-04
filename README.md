# DigitGan
This repository uses basic generative adversarial neural network to try to create original handwritten digits using the MNIST data set.  
For the GAN, the generator is a dense connected neural network with dropout, and the discriminator is a convolutional neural network.

GANs have proven to be excellent networks for producing original images given a dataset to learn from, some of the better images produced
by this network will be selected and posted on here so that they can be viewed.

Also, future work for this project might be posted here.

Future ideas/brainstorming:

Maybe cycle between different discriminators (One for determining if image is fake and one for)
Also, another idea is to have another intermediate network that removes all of the small splotches on the side

Separate idea:
Use this network but 
Maybe have some sort of random seed that makes half of the pixels random colors the rest black
For seed put first 10 as completely random, second ten (or whatever we are comparing to target) as the categorical digit
Then have a network that matches this to the nearest digit (whatever the seed)


