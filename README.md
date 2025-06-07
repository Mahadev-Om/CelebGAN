# CelebGAN
Built a custom GAN using TensorFlow and Keras to generate photorealistic celebrity faces from the CelebA dataset. Tackled mode collapse with label smoothing, dropout, and tuned optimizers. Visual callbacks tracked progress. A fusion of technical depth and creative vision in generative AI, pushing realism and stability in GANs.

This repository captures my work developing a custom Generative Adversarial Network (GAN) to generate photorealistic celebrity faces, leveraging the CelebA dataset. I engineered tailored training loops with techniques such as label smoothing, dropout, and carefully calibrated optimizers to overcome classic GAN pitfalls like mode collapse and training instability. Using TensorFlow and Keras, I implemented visual callbacks that track generation progress, ensuring consistent improvement and visual quality. This project exemplifies my rare blend of technical mastery and creative intuition in deep learning—crafting generative models that push the boundaries of visual realism. Beyond engineering, it reflects my commitment to understanding and solving nuanced challenges intrinsic to GAN training, positioning this work as a standout example in generative AI research.           

## Overview

CelebGAN generates realistic celebrity faces by training a GAN with optimized loss curves, custom callbacks, and visual monitoring.

## Core Features

  Generator + Discriminator (DCGAN-like architecture)
  Dropout, label smoothing, and BatchNorm
  GANMonitor for image sampling every few epochs

## Tech Stack

  TensorFlow, Keras, Matplotlib
  CelebA dataset (cropped & resized)
  Custom training loops with progress visualizations

## Challenges Tackled

  Mode collapse
  Training instability
  Vanishing gradients

## Structure

  `dataset/` — CelebA images
  `gan/` — Training loop, models
  `samples/` — Generated outputs across epochs

## Status

Model successfully trained for 100+ epochs  
Sample generations monitored & improved  
