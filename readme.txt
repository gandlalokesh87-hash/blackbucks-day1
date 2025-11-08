MNIST GAN

This project demonstrates a Generative Adversarial Network (GAN) trained on the MNIST handwritten digits dataset. The goal is to generate new, realistic digit images by having two neural networks compete and learn from each other.

Overview

The notebook builds and trains a GAN consisting of two main parts:

Generator – creates new digit images from random noise.

Discriminator – tries to distinguish real images (from the dataset) from fake ones (created by the generator).

During training, both models improve together: the generator learns to make convincing images, and the discriminator learns to detect them more accurately.

Features

Loads and preprocesses the MNIST dataset.

Defines and trains the generator and discriminator networks.

Alternates training between the two models for balanced learning.

Displays generated samples at different epochs to track progress.

Saves trained models and generated outputs for reuse.

Requirements

You’ll need a Python environment with deep learning and visualization libraries such as TensorFlow or PyTorch, NumPy, and Matplotlib.

How to Run

Open the notebook file in Jupyter and run the cells in order. The training process will display generated digits as the model improves over time.

File Structure

The repository contains a single notebook file named mnist_gan.ipynb, which includes the complete workflow from dataset loading to result visualization.

Results

After sufficient training, the generator produces realistic handwritten digits that closely resemble those in the MNIST dataset. The notebook includes visualizations showing how generated images evolve and improve across epochs.

Future Improvements

Experiment with deeper or convolutional architectures such as DCGAN or WGAN.

Use techniques like batch normalization and learning rate scheduling for better stability.

Try training on different image datasets to generalize the model.

License

This project is released under the MIT License and can be freely used and modified.