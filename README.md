# DCGAN for MNIST Handwritten Digits Generation

A TensorFlow/Keras implementation of Deep Convolutional Generative Adversarial Network (DCGAN) to generate realistic handwritten digits from the MNIST dataset.

![Sample Output](https://tensorflow.org/images/gan/dcgan.gif)  
*Example of generated images after 50 epochs of training.*

## 📌 Table of Contents

### 🌟 Overview
This project demonstrates how to train a DCGAN to generate synthetic handwritten digits (28x28 pixels) using TensorFlow 2.x. The generator learns to create realistic images, while the discriminator tries to distinguish real vs. fake images.

### ✨ Key Features
- **DCGAN Architecture**: Uses `Conv2DTranspose` layers in the generator and `Conv2D` layers in the discriminator.
- **Custom Training Loop**: Implemented with `tf.GradientTape`.
- **Progress Visualization**: Saves generated images during training to create a GIF.
- **Checkpointing**: Model weights are saved every 15 epochs.

## 📦 Dependencies
- Python 3.8+
- TensorFlow 2.x
- Matplotlib
- NumPy
- imageio (for GIF generation)

