# Variational_Autoenconder
used different VAEs to identify distinct phenotypes in my cells
the data i 40x40 images. The image data is currently private and will not be made avalible till after publication. 
In the past i worked with linear VAE, VAE, bVAE and MMD-VAE. 
In this notebook I have only two VAE codes the bVAE and MMD-VAE, which I found the most useful in identifying phenotypes.
I have tested this autoencoder for cytoplasm, mitochondria, vacuole, and nucleus 
The code is a bit messy as I am inputting new data and consistently playing with the different latent values. I found that a simple linear regression and k means proved to be the most efficient. 
