# 🧠 Handwritten Digit Classification using ANN

This project implements a **Handwritten Digit Classification system** using an **Artificial Neural Network (ANN)**.  
It is part of my learning journey in **Deep Learning**, where I explored how neural networks are inspired by human neurons and how they learn patterns from data.

The model is trained on the **MNIST dataset** and tested using **custom handwritten digit inputs** provided through a simple **Tkinter GUI**.

---

## 📌 Project Overview

- **Model Type:** Artificial Neural Network (ANN)
- **Dataset:** MNIST Handwritten Digits
- **Task:** Multi-class classification (digits 0–9)
- **Interface:** Tkinter GUI
- **Frameworks:** TensorFlow & Keras

---

## 🧠 Model Architecture

- **Input:** 28 × 28 grayscale image
- **Flatten Layer:** Converts image into a 1D vector
- **Hidden Layer:** Dense layer with 128 neurons and ReLU activation
- **Output Layer:** Dense layer with 10 neurons and Softmax activation

### 🔹 Activation Functions
- **ReLU:** Hidden layer
- **Softmax:** Output layer (used for multi-class classification)

---

## 🖥️ GUI (Tkinter)

A simple **Tkinter-based GUI** was created to:
- Draw handwritten digits
- Clear and redraw inputs
- Capture the drawn image
- Preprocess it and send it to the trained ANN model
- Display the predicted digit

⚠️ The GUI is designed for **personal experimentation**, where I provide the input images to observe how the model behaves on unseen data.

---

## 📊 Learning Outcomes

This project helped me understand:
- Working of Artificial Neural Networks
- Role of activation functions in classification tasks
- Image preprocessing techniques
- Model training and evaluation
- Practical challenges such as **overfitting**

---

## 🚧 Limitations & Future Improvements

- The ANN sometimes misclassifies digits
- Increasing neurons or epochs caused overfitting
- Planned improvements include:
  - Using **Convolutional Neural Networks (CNNs)**
  - Applying **Dropout and Regularization**
  - Improving image preprocessing
  - Deploying the model as a **web application**

---

## 🛠️ Languages & Tools

### 🔹 Language
- Python

### 🔹 Libraries & Frameworks
- TensorFlow
- Keras
- NumPy
- Pillow (PIL)

### 🔹 GUI
- Tkinter

### 🔹 Concepts Used
- Artificial Neural Networks (ANN)
- Multi-class Classification
- Image Preprocessing
- Overfitting

---

## 📂 How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone <your-repository-link>

