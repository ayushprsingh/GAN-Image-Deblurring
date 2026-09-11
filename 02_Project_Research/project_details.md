# Project Details

## Project Title

Method for Smoothing the Blur Images by De-blurring Them Using GAN

## Project Domain

Artificial Intelligence / Deep Learning / Computer Vision

## Problem

Image blur can occur due to camera motion, object movement, defocus and other imaging conditions. Blur reduces image sharpness and can hide important visual details. Recovering a sharp image from a blurred observation is a challenging image restoration problem.

## Proposed Idea

The project aims to develop a GAN-based image deblurring system that takes a blurred image as input and generates a sharper restored image.

## Basic Workflow

Blurred Image
↓
Image Preprocessing
↓
GAN Generator
↓
Restored Image
↓
PSNR / SSIM Evaluation

## GAN Components

### Generator

The generator receives a blurred image and attempts to produce a restored/sharp image.

### Discriminator

The discriminator attempts to distinguish between real sharp images and generated restored images. Its feedback helps the generator produce more realistic results.

## Main Objective

To develop a GAN-based image deblurring system capable of restoring sharper images from blurred input images.

## Specific Objectives

1. Study existing image deblurring techniques.
2. Prepare suitable training data containing blurred and sharp images.
3. Develop a GAN-based image restoration model.
4. Train the model to reconstruct sharper images.
5. Evaluate the model using PSNR and SSIM.
6. Perform visual comparison between blurred and restored images.
7. Integrate the trained model into a web-based application.
8. Analyze limitations and future improvements.

## Expected Output

The system should accept a blurred image and produce a visually improved/deblurred image.

## Evaluation

The project will use:

- Visual comparison
- PSNR
- SSIM

## Future Scope

Possible future improvements include larger and more diverse datasets, real-world blur, improved GAN architectures, better perceptual losses, faster inference and deployment on practical devices.
