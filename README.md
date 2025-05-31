# Autoencoder-Based Image Reconstruction

This project explores the use of **autoencoders** — a class of unsupervised neural networks — to perform image reconstruction and dimensionality reduction.  
As part of the PRAD Lab curriculum, this project demonstrates how autoencoders can effectively compress and reconstruct image data, making them useful for noise removal, anomaly detection, and representation learning.

---

## Objectives

- Understand and implement the structure of autoencoders using PyTorch.
- Train the model on image datasets (e.g., MNIST) for feature extraction and reconstruction.
- Visualize the performance of the encoder-decoder architecture on input images.

---

## Key Features

- **Autoencoder Architecture**: Custom-built convolutional encoder and decoder using PyTorch.
- **Reconstruction Evaluation**: Compare original vs. reconstructed images for qualitative analysis.
- **Loss Monitoring**: Track training and validation loss curves over epochs.
- **Dimensionality Compression**: Learn compact image representations with fewer parameters.

---

## Tech Stack

- Python  
- PyTorch  
- NumPy, Matplotlib  
- Google Colab / Jupyter Notebook  

---

## Sample Results

- **Original Image** →
- **Reconstructed Output** → (visibly similar with reduced information loss)
- Plotted loss curve shows steady convergence with low reconstruction error.

---

## Future Enhancements

- Experiment with denoising autoencoders.
- Add variational autoencoder (VAE) extension.
- Apply to more complex datasets like CIFAR-10.

