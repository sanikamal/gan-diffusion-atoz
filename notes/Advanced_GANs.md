## BigGAN
The BigGAN is an approach to pull together a suite of recent best practices in training GANs
and scaling up the batch size and number of model parameters. As its name suggests, the
BigGAN is focused on scaling up the GAN models. This includes GAN models with:

- More model parameters (e.g. many more feature maps).
- Larger Batch Sizes (e.g. hundreds or thousands of images).
- Architectural changes (e.g. self-attention modules).

The resulting BigGAN generator model is capable of generating high-quality 256 × 256 and
512 × 512 images across a wide range of image classes.

## Progressive Growing GAN

Progressive Growing GAN is an extension to the GAN training process that allows for the stable
training of generator models that can output large high-quality images. It involves starting with
a very small image and incrementally adding blocks of layers that increase the output size of
the generator model and the input size of the discriminator model until the desired image size
is achieved. Perhaps the most impressive accomplishment of the Progressive Growing GAN is
the generation of large 1024 × 1024 pixel photorealistic generated faces.

## StyleGAN

The Style Generative Adversarial Network, or StyleGAN for short, is an extension to the GAN
architecture that proposes large changes to the generator model. This includes the use of a
mapping network to map points in latent space to an intermediate latent space, the use of
the intermediate latent space to control style at each point in the generator model, and the
introduction to noise as a source of variation at each point in the generator model. The resulting
model is capable not only of generating impressively photorealistic high-quality photos of faces,
but also offers control over the style of the generated image at different levels of detail through
varying the style vectors and noise. For example, blocks of layers in the synthesis network at
lower resolutions control high-level styles such as pose and hairstyle, blocks at higher resolutions
control color schemes and very fine details like freckles and placement of hair strands.
