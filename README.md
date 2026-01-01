# Ai project based on DCGAN to Generate Anime Faces

The GAN architecture has several applications across different industries.
- Generate images
- Generate training data for other models
- Complete missing information
- Generate 3D models from 2D data

The face is like the dataset given

to do this project we build **Generator** and **Discriminatore** Functions, 

Take a look to understand **GAN** (Generative Adversarial Network)


How does a generative adversarial network work?

A generative adversarial network system comprises two deep neural networks—the generator network and the discriminator network. Both networks train in an adversarial game, where one tries to generate new data and the other attempts to predict if the output is fake or real data.

Technically, the GAN works as follows. A complex mathematical equation forms the basis of the entire computing process, but this is a simplistic overview:

    The generator neural network analyzes the training set and identifies data attributes
    The discriminator neural network also analyzes the initial training data and distinguishes between the attributes independently
    The generator modifies some data attributes by adding noise (or random changes) to certain attributes
    The generator passes the modified data to the discriminator
    The discriminator calculates the probability that the generated output belongs to the original dataset
    The discriminator gives some guidance to the generator to reduce the noise vector randomization in the next cycle

The generator attempts to maximize the probability of mistake by the discriminator, but the discriminator attempts to minimize the probability of error. In training iterations, both the generator and discriminator evolve and confront each other continuously until they reach an equilibrium state. In the equilibrium state, the discriminator can no longer recognize synthesized data. At this point, the training process is over.
