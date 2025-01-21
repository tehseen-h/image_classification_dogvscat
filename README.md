# 🐶🐱 Dog vs Cat Classification Using Deep Learning

This project is a deep learning-based image classification model that identifies whether an image contains a **dog** or a **cat**. Built using TensorFlow and Keras, this project demonstrates the power of convolutional neural networks (CNNs) in solving binary classification tasks with high accuracy.

---

## 🚀 Project Overview

- **Dataset**: The project uses the popular [Dogs vs Cats dataset](https://www.kaggle.com/salader/dogs-vs-cats) from Kaggle.
- **Model Architecture**:
  - Convolutional layers for feature extraction.
  - MaxPooling layers for dimensionality reduction.
  - Fully connected layers for classification.
  - Activation function: ReLU for hidden layers and sigmoid for output.
- **Preprocessing**: 
  - Images are resized to 256x256 pixels.
  - Normalization (pixel values scaled between 0 and 1).
- **Loss Function**: Binary Crossentropy.
- **Optimizer**: Adam.
- **Evaluation Metric**: Accuracy.

---

## 🛠 How It Works

1. **Dataset Preparation**: The dataset is downloaded using KaggleHub and split into training and validation sets.
2. **Model Training**: A CNN model is trained for 10 epochs on the dataset.
3. **Prediction**: The model predicts whether an unseen image is of a dog or a cat.

---

## 📂 Project Structure

