"""
README.md

# 🧠 Deep Neural Network for Multiclass Classification (Softmax + ReLU + sigmoid)

This project demonstrates a deep neural network implemented **from scratch using NumPy**, capable of **multiclass classification** using **softmax activation** in the output layer. The model is trained using manually-coded forward and backward propagation, gradient descent, and includes L2 regularization.

---

## 📌 Project Overview

- **Dataset:** Synthetic data generated using `make_classification` from `sklearn`.
- **Task:** Classify data into multiple classes using a deep neural network.
- **Framework:** Fully implemented using `NumPy` only (no ML libraries like TensorFlow or PyTorch).

---

## ⚙️ Model Architecture

- **Input Layer:** 10 features
- **Hidden Layer 1:** 100 neurons, ReLU activation
- **Hidden Layer 2:** 50 neurons, ReLU activation
- **Output Layer:** 2 neurons (softmax activation for multiclass classification)

---

## 🚀 Key Features

- Custom implementation of:
  - ReLU and Softmax activations
  - Forward propagation
  - Backpropagation with gradient computation
  - L2 Regularization (weight decay)
  - Accuracy and loss reporting
- Plotting of training loss using `matplotlib`

---

## 🛠️ Training Details

- **Loss function:** Cross-entropy
- **Optimizer:** Vanilla gradient descent
- **Regularization:** L2 with tunable `λ` (lambda)
- **Learning rate:** 0.1
- **Epochs:** 5000

---

## 📈 Output

- Prints the final training loss
- Prints training accuracy
- Shows a graph of loss over epochs

---

## 📊 Accuracy Calculation

The prediction is based on the highest probability in the softmax output. Accuracy is the ratio of correct class predictions to the total number of samples.

---

## 📦 Dependencies

Make sure you have the following Python libraries installed:

```bash
pip install numpy matplotlib scikit-learn
