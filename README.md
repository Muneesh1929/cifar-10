# 🖼️ CIFAR-10 Image Classification with CNN

> Training a Convolutional Neural Network (CNN) to classify 60,000 images from the CIFAR-10 dataset into 10 categories.

## 🔹 Dataset
- CIFAR-10: 50,000 training images, 10,000 test images
- 10 categories: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck

## 🔹 Approach
1. **Preprocessing**
   - Feature scaling (normalization /255)
   - Train-test split with validation

2. **Model Architecture**
   - Multiple **Conv2D** + **MaxPooling2D** layers
   - Dropout for regularization
   - Dense layers for classification
   - Output: Softmax activation (10 classes)

3. **Training**
   - Optimizer: Adam
   - Loss: Sparse Categorical Crossentropy
   - Epochs: 10, Batch size: 64
   - Achieved **~91% training accuracy** and **~75% test accuracy**

4. **Prediction Examples**
   - Classified external images like `cat.jpeg`, `ship.jpg`, `truck.jpg`, etc.

## 🔹 Tech Stack
Python · TensorFlow · Keras · CNN · Computer Vision

---

✨ “Teaching machines to see the world — one image at a time.”
