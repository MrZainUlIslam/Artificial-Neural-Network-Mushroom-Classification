# Mushroom Classification using Artificial Neural Networks

A complete implementation of a multi-class classification Artificial Neural Network (ANN) from scratch to classify mushrooms as edible or poisonous using the UCI Mushroom Dataset.

## 🍄 Project Overview

This project demonstrates the implementation of a neural network with:
- Forward and Backward Propagation
- ReLU Activation Function
- Softmax Output Layer for Multi-class Classification
- Adam Optimizer
- Xavier Weight Initialization
- Cross-entropy Loss Function

## 📊 Dataset

The project uses the **Mushroom Dataset** containing 8124 instances of mushrooms with 22 categorical features. The target variable classifies mushrooms as:
- **Edible** (e)
- **Poisonous** (p)

### Dataset Features
- cap-shape, cap-surface, cap-color, bruises, odor, gill-attachment, gill-spacing, gill-size, gill-color, stalk-shape, stalk-root, stalk-surface-above-ring, stalk-surface-below-ring, stalk-color-above-ring, stalk-color-below-ring, veil-type, veil-color, ring-number, ring-type, spore-print-color, population, habitat

## 🛠️ Implementation Details

### Neural Network Architecture
- **Input Layer**: 95 features (after one-hot encoding)
- **Hidden Layer**: 8 neurons with ReLU activation
- **Output Layer**: 2 neurons with Softmax activation
- **Loss Function**: Cross-entropy loss
- **Optimizer**: Adam optimizer with learning rate 0.01

### Key Features
1. **Custom Activation Functions**: ReLU for hidden layer, Softmax for output
2. **Advanced Optimization**: Adam optimizer with momentum and adaptive learning rates
3. **Proper Weight Initialization**: Xavier/Glorot initialization
4. **Comprehensive Evaluation**: Training and test accuracy metrics
5. **Visualization**: Loss convergence curve

## 📈 Results

The model achieves:
- **Training Accuracy**: ~99-100%
- **Test Accuracy**: ~99-100%
- **Loss Convergence**: Smooth decrease over epochs

## 🚀 Installation & Usage

### Prerequisites
```bash
pip install numpy pandas matplotlib scikit-learn
