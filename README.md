# Learning from Karpathy's Neural Networks Series

This repository contains my implementation and study notes following Andrej Karpathy's neural networks video series. The code focuses on building neural networks from scratch to better understand their fundamental concepts.

## Project Structure

- `1-micrograd.ipynb`: Implementation of a small autograd engine and a neural network from scratch
  - Includes Value class for automatic differentiation
  - Neural network implementation with forward/backward propagation
  - Training loop and visualization capabilities

## Key Concepts Covered

- Automatic Differentiation
- Backpropagation
- Neural Network Architecture
- Gradient Descent
- Loss Functions
- Training Process

## Requirements

```python
import math
import random
import graphviz  # for visualization
```

## Installation

1. Clone this repository
2. Install dependencies:
```bash
pip install graphviz
```
3. Make sure you have Graphviz installed on your system:
   - macOS: `brew install graphviz`
   - Ubuntu: `sudo apt-get install graphviz`
   - Windows: Download from the Graphviz website

## Usage

Open the Jupyter notebooks to see the implementations and explanations:
```bash
jupyter notebook
```

## References

- [Neural Networks: Zero to Hero](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) by Andrej Karpathy
- [micrograd](https://github.com/karpathy/micrograd) - Original repository

## License

MIT License (or specify your chosen license) 