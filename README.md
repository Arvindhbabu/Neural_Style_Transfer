# Neural Style Transfer

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/) [![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)](https://www.tensorflow.org/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview
This project implements neural style transfer, a technique that blends the content of one image with the artistic style of another. It uses a pre-trained model from TensorFlow Hub (Magenta's arbitrary image stylization) to generate stylized images efficiently. The implementation is in a Jupyter Notebook, allowing users to load custom content and style images, apply the transfer, and visualize results with Matplotlib.

Neural style transfer leverages deep learning to extract content features from one image and style features (like textures and colors) from another, combining them into a new image. This project provides an accessible way to explore computer vision and generative AI without custom training.

## Problem Statement
Implement neural style transfer to apply the artistic style of one image to the content of another using a pre-trained model from TensorFlow Hub. The system should load content and style images from local paths or URLs, perform the stylization process, and visualize the resulting stylized image, showcasing how convolutional neural networks can separate and recombine content and style representations for creative image generation without requiring model training.

## Features
- **Image Loading**: Supports loading images from local files or URLs, with resizing for efficient processing.
- **Pre-trained Model**: Utilizes TensorFlow Hub's arbitrary image stylization model for fast style transfer.
- **Stylization**: Applies style from a reference image to a content image.
- **Visualization**: Displays the stylized output using Matplotlib.
- **Extensible**: Easily swap content/style images or experiment with different models.

## Requirements
- Python 3.x
- Jupyter Notebook (or JupyterLab) for running the `.ipynb` file
- Required packages (installed via pip in the notebook):
  - tensorflow
  - tensorflow-hub
  - matplotlib
  - numpy (implicit via tensorflow)
  - pillow (for PIL)
  - requests (for URL-based image loading)
