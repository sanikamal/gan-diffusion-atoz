#  Pix2Pix Generative Adversarial Network
The Pix2Pix GAN is a general approach for image-to-image translation. It is based on the conditional generative adversarial network, where a target image is generated, conditional on a given input image. In this case, the Pix2Pix GAN changes the loss function so that the generated image is both plausible in the content of the target domain, and is a plausible translation of the input image.

## Pix2Pix GAN for Image-to-Image Translation

Pix2Pix is a Generative Adversarial Network, or GAN, model designed for general purpose image-to-image translation.

The approach was presented by [Phillip Isola](http://web.mit.edu/phillipi/), et al. in their 2016 paper titled “[Image-to-Image Translation with Conditional Adversarial Networks](https://arxiv.org/abs/1611.07004)” and presented at [CVPR in 2017](https://ieeexplore.ieee.org/abstract/document/8100115).

The GAN architecture is an approach to training a generator model, typically used for generating images. A discriminator model is trained to classify images as real (from the dataset) or fake (generated), and the generator is trained to fool the discriminator model.

The Conditional GAN, or cGAN, is an extension of the GAN architecture that provides control over the image that is generated, e.g. allowing an image of a given class to be generated. Pix2Pix GAN is an implementation of the cGAN where the generation of an image is conditional on a given image.

The generator model is provided with a given image as input and generates a translated version of the image. The discriminator model is given an input image and a real or generated paired image and must determine whether the paired image is real or fake. Finally, the generator model is trained to both fool the discriminator model and to minimize the loss between the generated image and the expected target image.

As such, the Pix2Pix GAN must be trained on image datasets that are comprised of input images (before translation) and output or target images (after translation).

This general architecture allows the Pix2Pix model to be trained for a range of image-to-image translation tasks.
