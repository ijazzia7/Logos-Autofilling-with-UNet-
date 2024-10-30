# Logo Auto-filling with GANs

This project uses a GAN-based approach to generate artistic and color-filled versions of logo outlines. The notebook trains a model that can enhance or "auto-fill" logo designs by coloring them and adding artistic elements, creating unique variations that can be used in logo design.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Model Architecture](#model-architecture)

## Project Overview
This project builds a **Generative Adversarial Network (GAN)** model designed to take in simple logo outlines and generate enhanced versions with color and style. The GAN is intended to assist designers by automating part of the creative process, making it possible to rapidly generate diverse logo variations. 

## Features
- **Outline-to-Art GAN**: Converts logo outlines into fully-colored artistic logos.
- **Customizable Layers**: Includes several options for customizing the generator's and discriminator's layers.
- **Training and Testing Pipelines**: Contains functions for training, testing, and saving model checkpoints.

## Model Architecture
The model uses a GAN architecture featuring:
1. **Generator**: Takes logo outlines as input and generates colored and stylized logo versions.
2. **Discriminator**: Assesses the generated images to ensure they look realistic and adhere to logo-style patterns.

### Key Components
- **Loss Functions**: Combines adversarial loss with pixel-wise loss for improved fidelity to original outlines.
- **Data Transformations**: Includes data normalization and resizing steps to ensure uniform input size for consistent training.
