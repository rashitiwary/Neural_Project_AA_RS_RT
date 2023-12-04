# Neural_Project_AAE

## Exploring GAN with the combination of VAE

The world of generative modeling has witnessed remarkable advancements in recent years, with Generative Adversarial Networks (GANs) and Variational Autoencoders (VAEs) standing as two prominent techniques. In our project, we aim to combine GAN and VAE for high quality image generation. By combining both techniques together, we aim to use each other’s pros and cons to produce superior generative results.

We will train the combined model on a set of images like dogs or celebrities and assess its evaluation based on different metrics such as loss and accuracy. We will also explore and learn about concepts like latent space visualization to further verify our results and approach. The approach that we are looking for is shown in the below figure.

![Approach](/Assets/approach.png)

The first half is our VAE, and second half uses the discriminator to predict whether the generated image is fake or real.

## Research and References

The starting point of deciding our project and the approach was through [1]. Through this project we aim to dive deep into the Gen AI and explore different techniques and tools associated with it. 

1. VAEGAN: A Collaborative Filtering Framework based on Adversarial Variational Autoencoders Xianwen Yu, Xiaoning Zhang, Yang Cao and Min Xia. [https://doi.org/10.24963/ijcai.2019/584](https://doi.org/10.24963/ijcai.2019/584)

2. [https://www.youtube.com/watch?v=0OgFW2W9LRY&ab_channel=NPTEL-NOCIITM](https://www.youtube.com/watch?v=0OgFW2W9LRY&ab_channel=NPTEL-NOCIITM)

3. [https://towardsdatascience.com/intuitively-understanding-variational-autoencoders-1bfe67eb5daf](https://towardsdatascience.com/intuitively-understanding-variational-autoencoders-1bfe67eb5daf)