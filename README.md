# Neural-Style-Transfer
Adaptive Instance Normalization (AdaIN) style transfer network in PyTorch


This repository contains a comprehensive implementation of an Adaptive Instance Normalization (AdaIN) style transfer network in PyTorch. The AdaIN approach allows for the stylization of content images using style images by aligning the mean and variance of content features with those of style features. This project includes the architecture for both the encoder and decoder modules, a custom dataset loader, and scripts for training and applying the style transfer. The encoder is based on a modified VGG network that captures content and style features, while the decoder is designed to reconstruct the stylized image from transferred features.

Key components of the repository include:

Encoder and Decoder Architecture: Custom implementations of convolutional neural networks for encoding content and style features and decoding them to generate stylized images.
AdaIN: The core function that performs the style transfer by adapting instance normalization.
Custom Dataset Loader: A utility for loading and transforming images from a directory, facilitating easy experimentation with different datasets.
Training Script: Facilitates the training of the AdaIN model using pairs of content and style images, with support for custom hyperparameters and CUDA acceleration.
Style Transfer Script: Allows for the application of style transfer to any content and style image pair, with adjustable strength of style transfer through the alpha parameter.
This implementation supports both CPU and GPU computation and includes options for adjusting the level of style transfer, making it a versatile tool for artists, designers, and researchers interested in exploring the possibilities of neural style transfer.
