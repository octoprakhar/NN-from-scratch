# 🧠 Neural Network from Scratch (Using Only NumPy)

This project implements a **fully-connected feedforward neural network** from scratch using **only NumPy** — no deep learning frameworks involved.
It focuses on understanding how forward propagation, backpropagation, and gradient descent work **under the hood** of libraries like TensorFlow and PyTorch.

---

## 🚀 Project Overview

The goal of this project was to build and train a **basic neural network** entirely from first principles — using only NumPy arrays and matrix operations.

This implementation includes:

* Manual weight initialization
* Forward propagation
* Activation functions (Sigmoid, ReLU)
* Backpropagation using partial derivatives
* Gradient descent optimization
* Training loop with loss monitoring

By doing this project, I gained a deep understanding of how each neuron updates its parameters during training and how errors propagate backward through the network.

---

## 🧩 Key Highlights

* **No ML libraries:** Implemented using only **NumPy** — every computation, gradient, and update step is manually defined.
* **Core mathematical intuition:** Derivatives and chain rule are coded explicitly.
* **End-to-end training:** The model learns simple patterns through multiple epochs using manually computed gradients.
* **Custom architecture flexibility:** The code is structured so that you can easily change the number of layers, neurons, or activation functions.

---

## ⚙️ Implementation Details

**Architecture:**

* Input layer → Hidden layer → Output layer
* Fully connected feedforward design
* Activation: Sigmoid / ReLU (configurable)

**Training Process:**

1. Initialize weights and biases randomly
2. Perform **forward pass**
3. Compute **loss** (Mean Squared Error)
4. Perform **backpropagation** to compute gradients
5. Update weights and biases via **gradient descent**

---

## 📈 Learning Outcome

This project helped me:

* Build confidence in neural network fundamentals
* Understand **how backpropagation actually computes weight updates**
* Develop intuition about **vanishing gradients** and why activations like ReLU matter
* Appreciate the power of high-level frameworks by understanding what they automate

---

## 🧠 Why This Project Matters

As a fresher, building this project from scratch shows:

* **Strong mathematical and implementation foundation**
* **Ability to connect theory with code**
* **Curiosity for how deep learning models actually learn**

It serves as a **building block** for more advanced architectures such as CNNs, RNNs, and LSTMs.

---

## 🛠️ Tech Stack

| Component    | Description                                                              |
| ------------ | ------------------------------------------------------------------------ |
| **Language** | Python                                                                   |
| **Library**  | NumPy                                                                    |
| **Concepts** | Forward Propagation, Backpropagation, Gradient Descent, Loss Computation |

---

## 💡 Future Improvements

* Add support for more activation functions (e.g., Tanh, Softmax)
* Implement mini-batch training
* Add momentum or Adam optimizer
* Visualize training loss and accuracy trends

---

## 📚 Author

**Prakhar Pathak**
Passionate about building AI models from scratch to deeply understand their mathematical and computational foundations.

---

⭐ *If you found this project interesting, check out my other deep learning projects — like my “RNN from Scratch” and “LSTM from Scratch” implementations!*
