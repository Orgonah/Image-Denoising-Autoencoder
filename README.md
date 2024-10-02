# Image-Denoising-Autoencoder

This repository contains a convolutional autoencoder for denoising images, specifically using the MNIST dataset.

## Introduction

This project demonstrates how to implement a deep convolutional autoencoder for image denoising, mapping noisy MNIST digit images to clean images.

## Model

A deep convolutional autoencoder is built using the Functional API of Keras.

## Training

The model is trained in two phases:

- Autoencoder is trained with clean images as both input and target.
- Autoencoder is retrained with noisy images as input and clean images as target to learn denoising.

## Usage

- Load and preprocess the MNIST dataset.
- Train the autoencoder with clean images.
- Retrain the autoencoder with noisy images.
- Predict and display denoised images.
