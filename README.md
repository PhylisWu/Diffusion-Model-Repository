# Diffusion-Model-Repository

### **What are Diffusion Models?**
Diffusion models are inspired by non-equilibrium thermodynamics. They define a Markov chain of diffusion steps to slowly add random noise to data and then learn to reverse the diffusion process to construct desired data samples from the noise. Unlike VAE or flow models, diffusion models are learned with a fixed procedure and the latent variable has high dimensionality (same as the original data).

Basically, the Diffusion Models work by continuously adding Gaussian noise to destroy the training data, and then learning to recover the data by reversing this noise process.

### **Quick Summary**
#### Pros: 
Tractability and flexibility are two conflicting objectives in generative modeling. Tractable models can be analytically evaluated and cheaply fit data (e.g. via a Gaussian or Laplace), but they cannot easily describe the structure in rich datasets. Flexible models can fit arbitrary structures in data, but evaluating, training, or sampling from 
these models is usually expensive. Diffusion models are both analytically tractable and flexible
Cons: Diffusion models rely on a long Markov chain of diffusion steps to generate samples, so it can be quite expensive in terms of time and compute. New methods have been proposed to make the process much faster, but the sampling is still slower than GAN.

#### Cons: 
Diffusion models rely on a long Markov chain of diffusion steps to generate samples, so it can be quite expensive in terms of time and compute. New methods have been proposed to make the process much faster, but the sampling is still slower than GAN.


### **Papers：**


* * *
##### Deep Unsupervised Learning using Nonequilibrium Thermodynamics 

Author:Jascha Sohl-Dickstein, Eric A. Weiss, Niru Maheswaranathan, Surya Ganguli

Link:https://arxiv.org/abs/1503.03585

ICML 2015.

* * *

##### Bayesian Learning via Stochastic Gradient Langevin Dynamics 

Authors:Max Welling, Yee Whye Teh

Link:https://www.stats.ox.ac.uk/~teh/research/compstats/WelTeh2011a.pdf

ICML 2011.

* * *

##### Generative Modeling by Estimating Gradients of the Data Distribution 

Authors:Yang Song, Stefano Ermon

Link:https://arxiv.org/abs/1907.05600

 NeurIPS 2019.

* * *

##### Improved Techniques for Training Score-Based Generative Models 

Authors:Yang Song, Stefano Ermon

Link:https://arxiv.org/abs/2006.09011

NeuriPS 2020.

* * *

##### Denoising Diffusion Probabilistic Models 

Authors:Jonathan Ho, Ajay Jain, Pieter Abbeel

Link:https://arxiv.org/abs/2006.11239

arxiv Preprint arxiv:2006.11239 (2020)

Code:https://github.com/hojonathanho/diffusion

* * *

##### Denoising Diffusion Implicit Models 

Authors:Jiaming Song et al

Link: https://arxiv.org/abs/2010.02502

arxiv Preprint arxiv:2010.02502 (2020)

Code:https://github.com/ermongroup/ddim

* * *

##### Improved Denoising Diffusion Probabilistic Models 

Authors:Alex Nichol & Prafulla Dhariwal

Link:https://arxiv.org/abs/2102.09672

arxiv Preprint arxiv:2102.09672 (2021)

Code:https://github.com/openai/improved-diffusion

* * *

##### Diffusion Models Beat GANs on Image Synthesis 

Authors:Prafula Dhariwal & Alex Nichol

Link:https://arxiv.org/abs/2105.05233

arxiv Preprint arxiv:2105.05233 (2021)

Code:https://github.com/openai/guided-diffusion


* * *

##### Classifier-Free Diffusion Guidance 

Authors: Jonathan Ho & Tim Salimans

Link:https://arxiv.org/abs/2207.12598

NeurIPS 2021 Workshop on Deep Generative Models and Downstream Applications.


* * *

Score-Based Generative Modeling through Stochastic Differential Equations 

Authors:Yang Song, et al.

Link:https://openreview.net/forum?id=PxTIG12RRHS

ICLR 2021.


* * *

##### GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models 

Authors:Alex Nichol, Prafulla Dhariwal & Aditya Ramesh, et al

Link:https://arxiv.org/abs/2112.10741

 ICML 2022.
 
* * *

#####  Cascaded Diffusion Models for High Fidelity Image Generation 

Authors:Jonathan Ho, et al.

Link:https://arxiv.org/abs/2106.15282

J. Mach. Learn. Res. 23 (2022): 47-1.

* * *

##### Hierarchical Text-Conditional Image Generation with CLIP Latents 

Authors: Aditya Ramesh et al. 

Link:https://arxiv.org/abs/2204.06125

arxiv Preprint arxiv:2204.06125 (2022).

* * *

##### Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding 

Authors:Chitwan Saharia & William Chan, et al. 

Link:https://arxiv.org/abs/2205.11487

arxiv Preprint arxiv:2205.11487 (2022).

* * *

##### High-Resolution Image Synthesis with Latent Diffusion Models 

Authors: Rombach & Blattmann, et al.

Link:https://arxiv.org/abs/2112.10752

 CVPR 2022
 
 Code:https://github.com/CompVis/latent-diffusion


* * *

##### Deep Unsupervised Learning using Nonequilibrium Thermodynamics 

Link:https://arxiv.org/abs/1503.03585）


