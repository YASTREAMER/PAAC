# PAAC Project
    Repo for trying out different CNN models.New models will be added soon. The repo uses pytorch as the main framework.

# List Of Datasets Used

    File name           | Dataset Used
    -------------       | -------------
    Mnsit.ipynb         | MNSIT
    CIFAR10.ipynb       | CIFAR10
    AD_CNN              | CIFAR10
    AutoencodersMNSIT   | MNSIT
    AutoencodersCIFAR10 | CIFAR10

# __Models description__ #

## __Mnist.ipynb__ ##

    The first model uses CNN to achieve an accuracy of:-90.25999999999999%.
    Nothing more will be added to tihs model after this.

## __CIFAR10.ipynb__ ##

    The second model added uses CNN on CIFAR10 dataset the achieves an accuracy of:-80.0%
    The mdoel is a basic CNN model. Nothing more will be added to this model after this.

## __Ad_CNN.ipynb__ ##

    This is the third model on list and uses advance CNN to classify CIFAR10 Dataset.
    The model is yet to be runned and hyperparameter tuning is till left.

##  __AutoencodersCIFAR10.ipynb__ ##

    This python files shows the power of autoencoders. They are very useful as they can compress a given input and thus are very useful for dimensionality reduction. This one uses Convolutional layers to achieve this on the CIFAR10 dataset.
##  __AutoencodersMNSIT.ipynb__ ##

    This python files shows the power of autoencoders. They are very useful as they can compress a given input and thus are very useful for dimensionality reduction. This one uses Linear fully connected layers to achieve this on the MNIST dataset.

## __variationalencoders.ipynb__ ##

    This python files shows the usage of variational encoders. They are very useful and thus can be used for dimensionality reduction.

    This file uses Linear fully connected layers to achieve this on the MNIST dataset.

## __variationalencodersCnn.ipynb__ ##

    This python files shows the usage of variational encoders. They are very useful and thus can be used for dimensionality reduction.

    This file uses Conv layer connected layers to achieve this on the CIFAR10 dataset. 


## __What are Autoencoders-- ##
    Autoencoders and variational autoencoders (VAEs) are types of neural network architectures used in unsupervised learning for representation learning and generative modeling.
    Autoencoders:

    An autoencoder is a type of neural network designed to learn efficient representations of data, typically by reducing the dimensionality of the input and then reconstructing it. It consists of an encoder and a decoder:

        Encoder: Takes the input data and maps it to a lower-dimensional representation (encoding).
        Decoder: Reconstructs the input data from the encoding.

    The network is trained to minimize the difference between the input and the reconstructed output. Autoencoders are useful for tasks like dimensionality reduction, feature learning, and denoising.
    Variational Autoencoders (VAEs):

    VAEs are a specific type of autoencoder that introduces probabilistic components into the model. Unlike traditional autoencoders, VAEs model the encoding as a probability distribution. This makes them more powerful for generative tasks and allows for sampling new data points from the learned distribution.

    The key components of a VAE include:

        Encoder: Similar to traditional autoencoders, it maps the input to a probability distribution in the latent space.
        Decoder: Reconstructs the input from samples drawn from the latent space distribution.

    The training objective of VAEs involves not only minimizing the reconstruction error but also ensuring that the learned latent space follows a specific probability distribution (usually a Gaussian distribution). This is achieved by introducing a regularization term that encourages the latent space to be close to a unit Gaussian.
    
    The probabilistic nature of VAEs makes them more flexible for 
    generating new data points. By sampling from the learned latent space distribution, VAEs can generate diverse and realistic variations of the input data.
## __To DO List__ ##

This is the TO DO LIST of the project

-[ ] Use VAE for dimensionality reduction

-[ ]  Try autoencoders on Galaxy dataset

-[ ] Train a model on a dimensionality reducted image(VAE)

