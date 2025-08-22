# My Neural Network Framework
## 🏗️ Project Architecture
```plaintext
## 🏗️ Project Architecture

my_nn_framework/
├── 📂 autograd.py
│   └── Value
├── 📂 nn.py
│   ├── Module
│   ├── Linear
│   ├── ReLU
│   └── NeuralNetwork
├── 📂 loss.py
│   ├── MSELoss
│   └── CrossEntropyLoss
├── 📂 optim.py
│   └── SGD
├── 📂 history.py
│   └── History
└── 📂 train.py
    └── Training Loop
```
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
