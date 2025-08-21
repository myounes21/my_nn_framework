# My Neural Network Framework
## 🏗️ Project Architecture

This project is organized into several distinct modules, each with a specific responsibility. The conceptual components of the neural network framework are mapped to the file structure as follows:

---

### 📂 `engine.py`
This file contains the core autograd engine.

* **Autograd System**
    * `Value`: The fundamental object that wraps data and enables automatic differentiation by building a computation graph.

---

### 📂 `nn.py`
This file contains all the building blocks for creating neural network architectures.

* **Module (Base Class)**: The foundation for all network components, providing methods like `parameters()` and `zero_grad()`.
* **Layers**: Individual operations that form the network.
    * `Linear`: A fully connected layer.
    * `ReLU`, `Sigmoid`, etc.: Activation functions.
* **NeuralNetwork**: The main class used to assemble layers into a complete model.

---

### 📂 `loss.py`
This file holds the functions used to evaluate the model's performance.

* **Loss Functions**
    * `MSELoss`: For regression tasks.
    * `CrossEntropyLoss`: For classification tasks.

---

### 📂 `optim.py`
This file contains the optimizers used to train the model by updating its parameters.

* **Optimizers**
    * `SGD`: Stochastic Gradient Descent.

---

### 📂 `history.py`
This file contains a utility class for logging and visualizing the training process.

* **History**
    * Methods to record and plot metrics like loss and accuracy.

---

### 📂 `train.py`
This is the main executable script that orchestrates the entire training process.

* **Training Loop**: The sequence of operations (forward pass, loss calculation, backward pass, and parameter updates) that constitutes the model training.
A simple neural network framework built from scratch in Python to understand the core concepts of deep learning. This project includes a custom autograd engine for automatic differentiation.

---

## Features

- [ ] **Autograd Engine**: A `Value` class that tracks operations to build a dynamic computation graph.
- [ ] **Modular Layers**: `Linear`, `ReLU`, and other activation layers.
- [ ] **Loss Functions**: `MSELoss` for regression and `CrossEntropyLoss` for classification.
- [ ] **Optimizer**: `SGD` optimizer for model training.
- [ ] **Visualization**: Plotting for training loss and accuracy.

---

## Setup and Installation

```bash
# Clone the repository
git clone [https://github.com/myounes21/my_nn_framework.git](https://github.com/myounes21/my_nn_framework.git)
cd my_nn_framework

# Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
