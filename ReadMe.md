Unlike FVBNs and VAE, GAN does not explicitly models the probability distribution p(s) that generates the training data. Instead, we model a generator G:z↦s. The generator G samples s∼p(s) from the latent variable z. Apart from the generator G, we create a discriminator D(x) which identified the samples from the generator G and the true samples from training data. While training the discriminator D, the generator G is also trained so that th generated samples cannot be identified by the discriminator. The advantages of GAN are low sampling cost and state-of-the-art in image generation. The disadvantage is that we cannot calculate the probability distribution pmodel(s) because we do not model any probability distribution, and we cannot infer the latent variable z from a sample.
# Requirements  
1. GAN Knowledge
2.Pytorch framework
3.GPU sopported PC
