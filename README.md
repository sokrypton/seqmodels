# seqmodels
![logo](https://github.com/sokrypton/seqmodels/blob/master/seqmodels.png?raw=true)

Generative models are often used to capture the multivariate distribution of related biological sequences. These include Position-Specific-Scoring-Matrices, Markov-Random-Fields (MRF), Multivariate-Gaussian (MG) models and most recently Auto-Encoders. In order better understand the difference between these models, we propose a unified autoencoder-like framework that consists of a single or series of fully-connected layer(s) between the inputs and outputs, with the objective of minimizing the difference between them. By doing so, we show that it is possible to interpolate between all of these models with a few trivial changes in between. More specifically, we reduce the difference between MRFs and MG models to a single change in the loss function, and show that the regularization techniques often used in MRF, when applied to MG, results in similar performance between the two models.

[Read more (arXiv)](https://arxiv.org/abs/1906.02598)

[ICML Slides](https://docs.google.com/presentation/d/1uXGsgV7Fxhut8_cfgbHrTx1IHboR9OFi9ZMmZT1HvJs)
[ICML Poster](https://docs.google.com/presentation/d/1z_7hw_tTfDUNeTiPuOPO5EdokhC76Sa9JpR4sD8UyOA)
