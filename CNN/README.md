Lab 7 — Implementing a Convolutional Neural Network (Keras): This is a Jupyter notebook that builds, trains, and evaluates a Convolutional Neural Network (CNN) on the MNIST handwritten digits dataset using TensorFlow/Keras.

📌 What this notebook does
- Problem: Multiclass classification (digits 0–9)
- Dataset: MNIST (60,000 train / 10,000 test grayscale images, 28×28)
- Workflow:
  - Load & split MNIST (keras.datasets.mnist)
  - Inspect shapes & visualize samples (Seaborn heatmap + helper plot_imgs)
  - Preprocess: normalize pixels to [0, 1], reshape to (H, W, 1)
  - Model: build a CNN (Conv2D + BatchNorm + ReLU) × 4 → Global Avg Pool → Dense(10)
  - Train: SGD optimizer (lr=0.1), Sparse Categorical Crossentropy (from_logits=True)
  - Evaluate: test loss/accuracy; visualize predictions
