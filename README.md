
# 🧠 Handwritten Digit Recognition using CNN (MNIST)

This project implements a Convolutional Neural Network (CNN) using Keras to recognize handwritten digits (0 to 9) from the MNIST dataset. It is a beginner-friendly deep learning project focused on image classification and model evaluation.

---

## 📌 Project Summary

- 📊 Trained on the MNIST dataset (60,000 training images and 10,000 test images)
- 🧠 CNN architecture with 3 Conv2D layers and 2 MaxPooling layers
- 🎯 Achieves high test accuracy (~98%) after 5 training epochs
- 📷 Includes visualization of predicted digits on sample images

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Google Colab or Jupyter Notebook

---

## 🧱 Model Architecture

```python
Input: 28x28 grayscale image
→ Conv2D (32 filters, 3x3) + ReLU
→ MaxPooling2D (2x2)
→ Conv2D (64 filters, 3x3) + ReLU
→ MaxPooling2D (2x2)
→ Conv2D (64 filters, 3x3) + ReLU
→ Flatten
→ Dense (64 units) + ReLU
→ Dense (10 units) + Softmax (for digit classification)


