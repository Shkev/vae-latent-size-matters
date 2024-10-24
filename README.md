# Why Bigger is Not Better: The Asymptotic Behavior of VAE Latent Space
A study of the asymptotic behavior of the size of the latent space of the Varational Autoencoder (VAE).

## Abstract

We study the effect of the dimensionality of the latent space of variational autoencoders (VAE) on the model’s ability to effectively reconstruct input data (encoding/decoding quality) as well as generate new images. We provide a source coding interpretation of the VAE, reframing the minimization of the ELBO loss as the creation of a minimal length source code. Under this framework, we prove that in the case where the posterior latent distribution is modelled as a normal distribution with i.i.d. components, increasing the latent dimension results in poor recovery of details in input data when considering the model’s reconstruction abilities and provide an explanation for the diminishing quality of generated data. We empirically show that these results hold beyond just the case of i.i.d. latent components.

### TL;DR

We prove that as the dimensionality of the latent space of the VAE gets infinitely large, the VAE's input reconstruction and data generation abilities.
