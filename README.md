# 🧠 Handwritten Digit Identifier using Neural Network

## 🔍 Project Overview
This project implements a basic neural network for classifying handwritten digits (0–9) from the **MNIST dataset** or any similar image dataset provided in CSV format.

You’ll learn to build and simulate the **forward propagation process** through multiple layers of a neural network using two approaches:

- ✅ A **procedural (functional)** model for simple 3-layer classification  
- ✅ A **flexible object-oriented** model that supports arbitrary-depth networks using class abstraction

---

## 🧩 Key Features

- ✅ Reads handwritten digit images from a CSV file  
- ✅ Scales image pixel values between 0 and 1  
- ✅ Builds a neural network with:
  - Input Layer: 784 neurons (28×28 pixels)
  - Hidden Layers: Configurable sizes
  - Output Layer: 10 neurons (for digits 0–9)  
- ✅ Uses **Sigmoid** activation in each layer  
- ✅ Computes output through **matrix multiplication and bias addition**  
- ✅ Object-oriented design enables building networks of **any depth dynamically**

---

## ⚙️ Technologies Used

- Python  
- NumPy  
- SciPy (sigmoid function)  
- IPython / Jupyter Notebook  
- *(Optional)* PIL & Matplotlib for visualization

---

## 🧪 Learning Objectives

- Understand **forward propagation** in neural networks  
- Learn the role of **weights**, **biases**, and **activations**  
- Use **object-oriented programming** to structure scalable ML code  
- Work with **real image data** in numerical form  

---

## 🧭 Possible Extensions

- Add **ReLU** or **Softmax** as alternative activation functions  
- Add **backpropagation** and training with **gradient descent**  
- **Save and load** weights for testing  
- Wrap into a **GUI** or **Flask API** for real-time digit prediction  
