# 👕 02-Vanilla-Autoencoder-FashionMNIST

A PyTorch implementation of a **Vanilla Autoencoder** trained on the **Fashion-MNIST** dataset to learn compressed latent representations and reconstruct grayscale clothing images.

This project is the second step in my Deep Learning learning journey, where I apply the same Autoencoder architecture used for MNIST to a more challenging image dataset and analyze how model performance changes with increased image complexity.

---

## 📌 Project Overview

An Autoencoder is an unsupervised neural network that learns to compress input data into a lower-dimensional latent representation and reconstruct it back to its original form.

Unlike handwritten digits, Fashion-MNIST contains clothing items with more complex shapes and patterns, making the reconstruction task more challenging.

---

## 🎯 Objectives

- Learn how the same Autoencoder architecture performs on a different dataset.
- Understand the impact of dataset complexity on reconstruction quality.
- Explore latent representation learning using Fashion-MNIST.
- Compare the results with the MNIST Autoencoder project.

---

## 🧠 Dataset

**Dataset:** Fashion-MNIST

- 60,000 Training Images
- 10,000 Test Images
- 10 Clothing Categories
- Image Size: 28 × 28
- Grayscale Images

### Classes

| Label | Class |
|------:|--------|
| 0 | T-shirt / Top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle Boot |

---

## 🏗️ Model Architecture

### Encoder

```
784
 ↓
256
 ↓
128
 ↓
64
 ↓
32
```

### Decoder

```
32
 ↓
64
 ↓
128
 ↓
256
 ↓
784
```

Activation Function:
- ReLU (Hidden Layers)
- Sigmoid (Output Layer)

Loss Function:
- Mean Squared Error (MSE)

Optimizer:
- Adam

---

## 📊 Results

The project includes:

- ✅ Training Loss Curve
- ✅ Original vs Reconstructed Images
- ✅ Reconstruction Error Visualization
- ✅ Saved Trained Model

---

## 💻 Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib

---

## 📈 Key Learnings

Through this project, I learned:

- Building and training a Vanilla Autoencoder using PyTorch.
- Applying the same architecture to a more challenging dataset.
- Understanding how image complexity affects reconstruction quality.
- Evaluating model performance using loss curves and reconstruction error.
- Reusing deep learning architectures across different datasets.

---

## 🔍 Comparison with Project 1

| MNIST | Fashion-MNIST |
|--------|---------------|
| Handwritten Digits | Clothing Images |
| Simpler Shapes | More Complex Shapes |
| Easier Reconstruction | More Challenging Reconstruction |
| Lower Reconstruction Error | Higher Reconstruction Error |

This project demonstrates that the same Autoencoder architecture can generalize to different datasets while highlighting the effect of dataset complexity on reconstruction performance.

---

## 🚀 Future Improvements

- Denoising Autoencoder
- Convolutional Autoencoder
- Variational Autoencoder
- Document Image Reconstruction
- OCR-based Information Extraction

---

## 📚 Deep Learning Learning Series

- ✅ 01 – Vanilla Autoencoder (MNIST)
- ✅ 02 – Vanilla Autoencoder (Fashion-MNIST)
- ⬜ 03 – Denoising Autoencoder
- ⬜ 04 – Convolutional Autoencoder
- ⬜ 05 – Variational Autoencoder
- ⬜ 06 – Document Image Reconstruction
- ⬜ 07 – Document OCR System

---

## 👩‍💻 Author

**Meenakshi Rakesh Pai**

B.Tech CSE (AI & ML)

Passionate about Deep Learning, Computer Vision, and building AI solutions for real-world problems.
