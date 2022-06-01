# Generative modeling 
Generative modelling is an unsupervised form of machine learning in which the model learns to find patterns in the 
data it is given. The model may generate new data on its own, which is related to the original training dataset, 
using this knowledge.VAEs, or variational autoencoders, give us a probabilistic way to describe these latent vectors. 
In a traditional autoencoder, we'd aim to represent each latent state attribute with a single variable. The StyleGAN 
is a development of the progressive GAN, which is a proposal for training generator models to synthesise massive high-quality
photographs by incrementally evolving both discriminator and generator models from minute to extensive pictures.
An autoencoder is a form of artificial neural network that is used to learn unsupervised data encodings. The goal 
of an autoencoder is to train the network to capture the most essential bits of the input image in order to learn 
a lower-dimensional representation (encoding) for a higher-dimensional data, often for dimensionality reduction.

# AnimeGAN version 1 and version2 

Layer normalisation of features is used in AnimeGA to avoid the network from generating high-frequency artefacts 
in the output images.However, because of the usage of instance normalisation, AnimeGAN is prone to producing 
high-frequency artefacts, which is the same reason that styleGAN produces high-frequency artefacts.
Total variation loss, in reality, is unable to totally eliminate the formation of high-frequency noise.

# Orion  
Orion is a machine learning package for detecting anomalies in unsupervised time series data. We provide a variety of
"confirmed" machine learning pipelines that discover unique patterns in time series data and flag them for expert assessment.
A number of automated machine learning tools developed by the MIT Data to AI Lab are used in the library.

# BLIP 

The information gain on model parameters is preserved by BLIP by updating the parameters at the bit level,
which is easily achieved using parameter quantization. To be more explicit, BLIP first trains a neural network with 
weight quantization on the new incoming task, then calculates information gain on each parameter provided by the task 
data to determine which bits should be frozen to avoid forgetting.
