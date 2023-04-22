# Generative Adversarial Networks
![gan](image/gan.png)

**Generative Adversarial Networks**, or **GANs** for short, are an approach to generative modeling using deep learning methods, devised by [Goodfellow et al](https://arxiv.org/abs/1406.2661). in 2014. 

Generative modeling is an unsupervised learning task in machine learning that involves automatically discovering and learning the regularities or patterns in input data in such a way that the model can be used to generate or output new examples that plausibly could have been drawn from the original dataset.

GANs are a clever way of training a generative model by framing the problem as a supervised learning problem with two sub-models. In a `GAN` setup, two differentiable functions, represented by neural networks, are locked in a game.The two players (the generator and the discriminator) have different roles in this framework.

The `generator` tries to produce data that come from some probability distribution. 

The `discriminator` acts like a judge. It gets to decide if the input comes from the generator or from the true training set.

## DCGAN

## Table of Contents
- [DCGAN Notebook](notebook/dcgan_mnist.ipynb)

# 🎨 GAN A to Z 🤖

Welcome to GAN A to Z, a collection of Jupyter notebooks and Python scripts that provide a comprehensive introduction to Generative Adversarial Networks (GANs).
## 📚 Overview

This repository contains a series of mini-projects that cover various aspects of GANs, from basic concepts to advanced techniques. Each project is presented as a Jupyter notebook and includes detailed explanations, code examples, and visualizations to help you understand how GANs work and how to use them.

The projects are organized in a logical order, starting with the basics of GANs and gradually building up to more advanced topics such as conditional GANs, Wasserstein GANs, and StyleGAN. You can follow the projects in order or jump straight to the topics that interest you.
## 🚀 Getting started

To get started, you'll need to install the dependencies listed in requirements.txt. You can do this by running:

pip install -r requirements.txt

Once you've installed the dependencies, you can run the Jupyter notebooks in the notebooks directory. Each notebook includes step-by-step instructions and code examples that you can run and experiment with.
## 📝 Contributing

If you find a bug or have a suggestion for a new project, please open an issue or submit a pull request. We welcome contributions from the community and are happy to help newcomers get started.
## 📄 License

This repository is licensed under the MIT License. See the LICENSE file for more information.
##🙏 Acknowledgments

We would like to thank the authors of the papers and tutorials that inspired this collection, as well as the open-source contributors who made this work possible.
## 📧 Contact

If you have any questions or feedback, please feel free to reach out to us at email@example.com.

We hope you find this collection useful and informative. Happy learning! 🤓




