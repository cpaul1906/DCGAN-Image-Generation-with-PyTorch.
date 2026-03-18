# DCGAN Image Generation with PyTorch

This project builds a Deep Convolutional Generative Adversarial Network (DCGAN) in PyTorch to generate synthetic images from random noise. It demonstrates a practical generative AI workflow including data preparation, adversarial training, generator and discriminator design, and visual evaluation of generated outputs.

## Overview

Generative Adversarial Networks are a foundational approach in generative AI because they learn to create new data samples by training two neural networks in competition. In this project, I implement a DCGAN architecture to generate realistic synthetic images and explore the dynamics of adversarial learning.

The notebook is designed to show an end-to-end deep learning workflow for image generation using modern neural network techniques.

## Project Goal

The goal of this project is to demonstrate how a generator network can learn to produce realistic image-like outputs by competing against a discriminator network trained to distinguish real images from synthetic ones.

## Tools and Technologies

- Python
- PyTorch
- NumPy
- Matplotlib
- Jupyter Notebook

## What the Notebook Does

This project includes the following steps:

- Loads and prepares image data for GAN training
- Normalizes image inputs for stable learning
- Builds a generator network to create synthetic images
- Builds a discriminator network to classify real vs. fake images
- Trains both models through adversarial optimization
- Monitors generator and discriminator loss during training
- Visualizes generated image outputs across training progress

## Model Summary

The notebook uses a Deep Convolutional GAN architecture with two core components:

### Generator
The generator learns to transform random noise vectors into synthetic images.

### Discriminator
The discriminator learns to separate real training images from images produced by the generator.

Through repeated adversarial updates, the generator improves its ability to fool the discriminator and create more realistic outputs over time.

## Evaluation

GAN evaluation is partly visual, so the notebook focuses on tracking training behavior and inspecting generated samples. The project evaluates whether the generator begins to produce coherent image structure and whether adversarial training remains stable.

## Business and Technical Relevance

This project demonstrates practical skills in:

- Generative AI
- Deep learning model architecture
- Adversarial training workflows
- Image synthesis
- PyTorch-based experimentation

Generative workflows like this have relevance in areas such as synthetic data generation, creative AI, computer vision research, simulation, and media applications.

## Next Steps

Potential future improvements include:

- Training on larger or more complex image datasets
- Comparing DCGAN performance against newer generative models
- Improving training stability with architecture and loss refinements
- Measuring output quality with additional evaluation techniques
- Extending the workflow to conditional image generation

## File

- `dcgan_image_generation_pytorch_portfolio.ipynb` — notebook containing data preparation, generator and discriminator training, adversarial learning workflow, and output visualization

## Note

This project was originally developed as graduate coursework and is being shared as part of my technical portfolio to demonstrate applied generative AI, deep learning workflow development, and hands-on experience with GAN-based image synthesis.

## Author

Christopher Paul
