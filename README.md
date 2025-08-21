# My Neural Network Framework
## 🏗️ Project Architecture

my_nn_framework/
│
├── 📂 engine.py
│   └── Autograd System
│       └── Value
│
├── 📂 nn.py
│   ├── Module (Base Class)
│   ├── Layers
│   │   ├── Linear
│   │   └── Activation (ReLU, etc.)
│   └── NeuralNetwork
│
├── 📂 loss.py
│   └── Loss
│       ├── MSELoss
│       └── CrossEntropyLoss
│
├── 📂 optim.py
│   └── Optimizer
│       └── SGD
│
├── 📂 history.py
│   └── History (Plotting & Logging)
│
└── 📂 train.py
    └── Training Loop (Orchestrator)

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
