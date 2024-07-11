# Score-Based Diffusion Models

## Introduction

Diffusion generative models are a class of deep learning models used for generating data that closely resembles a given training dataset. They differs substantially from other approaches, like generative adversarial networks (GANs) and variational auto-encoders (VAEs). Notably, it was one of the core ingredients of OpenAI's recent [DALL·E 2](https://openai.com/index/dall-e-2/) system for converting natural language descriptions to detailed images.

Diffusion generative models use the following idea. Samples from some distribution (e.g. of images) are gradually corrupted with more and more noise until they become unrecognizable static—this is the 'diffusion'. We then learn to reverse this mapping, so that we can turn unrecognizable static into a sample from our distribution of interest. Because it's easy to sample unrecognizable static, the mapping allows us to easily sample from our target distribution.

This repository is thus dedicated to exploring the intricacies of these score-based diffusion models by implementing them from scratch. The journey began with an immersion into Harvard's remarkable seminar series on Machine Learning from scratch, where I successfully completed their comprehensive tutorial on score-based diffusion models.


## Motivation
Understanding the inner workings of score-based diffusion models is crucial in the realm of Generative AI for image modeling. This project serves as a hands-on exploration, providing a
practical and insightful perspective on the construction of these models from the ground up.

## Reading
[2021 Song et al.] [Score-Based Generative Modeling through Stochastic Differential Equations ](https://openreview.net/forum?id=PxTIG12RRHS)

[2019 Song and Ermon][Generative Modeling by Estimating Gradients of the Data Distribution](https://proceedings.neurips.cc/paper/2019/hash/3001ef257407d5a371a96dcd947c7d93-Abstract.html)

## Acknowledgments
Special thanks to Harvard's Drugowitsch Lab for their exceptional seminar series that laid the groundwork for this project.

Happy coding and learning!
