## CycleGAN
A limitation of the Pix2Pix model is that it requires a dataset of paired examples before and
after the desired translation. There are many image-to-image translation tasks where we may
not have examples of the translation, such as translating photos of zebra to horses. There are
other image translation tasks where such paired examples do not exist, such as translating art of
landscapes to photographs. The CycleGAN is a technique that involves the automatic training
of image-to-image translation models without paired examples. The models are trained in an
unsupervised manner using a collection of images from the source and target domain that do
not need to be related in any way. The CycleGAN is an extension of the GAN architecture
that involves the simultaneous training of two generator models and two discriminator models.
One generator takes images from the first domain as input and outputs images for the second
domain, and the other generator takes images from the second domain as input and generates
images from the first domain. Discriminator models are then used to determine how plausible
the generated images are and update the generator models accordingly. The CycleGAN uses an
additional extension to the architecture called cycle consistency. This is the idea that an image
output by the first generator could be used as input to the second generator and the output of
the second generator should match the original image. The reverse is also true: that an output
from the second generator can be fed as input to the first generator and the result should match
the input to the second generator.
