# Tensor Flow Generative Models

A simple library for building and experimenting with generative models. 

# GAN

To start out, we write functions to make generator, discriminator, JS and Wasserstein losses and training loop.

Training loop will take a visualization script. 

visualize : real, generated -> output a picture

# VAE
We will make encoder, latent_sampler (with kl-loss) and decoder.

We will add various probabilistic loss capabilities as well as sampling so we can make various empirical Bayes models. 

# Future:

Importance samplling weights GAN for causal inference.

Categorical latent space. 

Conv nets, cycle gans, graph neural network.

Analysis, model comparison, diagnostics toolbox.

Make pytorch etc versiou.