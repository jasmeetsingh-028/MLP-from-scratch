# MLP-from-scratch
This repository contains a step-by-step implementation of a neural network from scratch, inspired by [Andrej Karpathy’s](https://www.youtube.com/watch?v=VMj-3S1tku0) excellent tutorial. The entire project is built using **pure Python**, without relying on deep learning frameworks — designed to give a clear understanding of forward and backward passes, computational graphs, and how a neural network actually learns.

Each notebook is focused on a specific concept and builds up progressively toward a fully working multi-layer perceptron (MLP).

---

## 📚 Notebook Overview

### `1. understanding_gradients.ipynb`
- Visualizes gradients in simple functions
- Uses the point-slope form to understand gradient descent intuitively
- Plots tangent lines to understand slope at a point

### `2. value_object.ipynb`
- Implements a custom `Value` object (similar to tensors in PyTorch)
- Supports basic mathematical operations (e.g., `+`, `*`, `**`)
- Builds a computational graph automatically during operations

### `3. graph_visualization.ipynb`
- Demonstrates visualizations of computation graphs built using the `Value` object
- Helps in understanding how expressions are represented as graphs

### `4. backward.ipynb`
- Implements backpropagation through the computational graph
- Explains the flow of gradients and how each node contributes
- Includes an implementation of the `tanh` activation function

### `5. neural_network.ipynb`
- Builds:
  - A single neuron
  - A layer of neurons
  - A full multi-layer perceptron (MLP)
- Includes a simple text dataset with 3 examples
- Implements a training loop using manual gradient updates

---

## 🚀 Why This Project?

This project is all about **learning by building**. By recreating the building blocks of neural networks from scratch, you’ll gain a much deeper intuition for:
- How gradients are computed and propagated
- What happens under the hood during training
- How frameworks like PyTorch or TensorFlow abstract these operations

---

## 📎 Resources

- [Karpathy's YouTube Tutorial](https://www.youtube.com/watch?v=VMj-3S1tku0)
- [My LinkedIn Post About the Project](https://www.linkedin.com/posts/jasmeet-singh-6118701b9_neuralnetworks-machinelearning-deeplearning-activity-7341147124006281216-y1XN?utm_source=share&utm_medium=member_desktop&rcm=ACoAADLZ6m0BQnIgAqQ_NFjjVxKa6EPV34WYs_Q)

---

Feel free to explore the notebooks, tweak things, and experiment!

> If you found this helpful or interesting, give the repo a ⭐ and let’s connect!

---

## 🧑‍💻 Author

**[Jasmeet Singh]**  
[LinkedIn](https://www.linkedin.com/in/jasmeet-singh-6118701b9/) • [Portfolio/Website](https://jasmeetsingh-028.github.io/jasmeet-portfolio.github.io//portfolio/)  
