# 🧠 Simple Neural Network from Scratch (NumPy)

This repository contains a simple implementation of a feedforward neural network built **from scratch using NumPy**.  
The model is trained to solve the classic **XOR classification problem**, which demonstrates how neural networks can learn non-linear decision boundaries.

This project is purely educational and avoids using any deep learning frameworks such as TensorFlow or PyTorch, so you can understand what happens behind the scenes.

---

## 🚀 Features
- One hidden layer neural network  
- Sigmoid activation function  
- Manual backpropagation  
- Gradient descent optimization  
- Binary classification  
- Trained on XOR dataset  

---

## 📊 Dataset (XOR Problem)

```python
x = np.array([
    [0, 0],
    [0, 1],
    [1, 0],
    [1, 1]
])

y = np.array([[0], [1], [1], [0]])
## 🎯 Purpose

The main goal of this project is to understand how neural networks work at a fundamental level by implementing one completely from scratch using NumPy.  
Instead of relying on high-level libraries like TensorFlow or PyTorch, this project focuses on the core concepts behind neural networks, such as:

- Forward propagation  
- Loss calculation  
- Backpropagation  
- Gradient descent optimization  
- Weight and bias updates  
- Matrix dimension handling  

By solving the XOR classification problem, this project demonstrates how neural networks can learn non-linear patterns, which cannot be solved using simple linear models. It is ideal for beginners who want a strong mathematical and conceptual foundation in machine learning.

---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/neural-network-from-scratch.git

2. Navigate to the project directory:
```bash
cd neural-network-from-scratch

3. Install the required dependency:
```bash
pip install numpy


4. Run the program:
```bash
python neural_network.py


5. You should see the output similar to:
```csharp
Predicting values:
[0 0] -> 0
[0 1] -> 1
[1 0] -> 1
[1 1] -> 0
