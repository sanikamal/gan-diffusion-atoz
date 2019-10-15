# Generative Adversarial Networks
![gan](image/gan.png)

`GANs` are generative models devised by [Goodfellow et al](https://arxiv.org/abs/1406.2661). in 2014. In a `GAN` setup, two differentiable functions, represented by neural networks, are locked in a game. The two players (the generator and the discriminator) have different roles in this framework.

The `generator` tries to produce data that come from some probability distribution. 

The `discriminator` acts like a judge. It gets to decide if the input comes from the generator or from the true training set.