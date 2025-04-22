# MNIST Handwritten Digit Recognition using CNN (TensorFlow)

This project uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras to classify handwritten digits from the MNIST dataset. The model achieves over 99% accuracy on the validation set, with data augmentation and regularization techniques for robust training.

## 🚀 Features
- Data preprocessing and normalization
- Data augmentation using `ImageDataGenerator`
- CNN model with Conv2D, MaxPooling, BatchNormalization
- Callbacks for:
  - Early stopping
  - TensorBoard logging
  - Learning rate reduction on plateau
- Model saving (`model.h5`)

## 🧠 Dataset
- [MNIST Handwritten Digits](http://yann.lecun.com/exdb/mnist/): 70,000 grayscale images of handwritten digits (0–9), size 28x28 pixels.

## 📊 Results
By epoch 26, the model achieves:
- **Training Accuracy**: 99.65%
- **Validation Accuracy**: 99.40%
- **Validation Loss**: 0.0185
