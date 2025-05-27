# Titanic Neural Network Classifier

This repository contains a neural network model implemented in Python using TensorFlow/Keras to predict the survival of passengers on the Titanic. The model is trained on the Titanic dataset provided by Seaborn, using features such as passenger class (`pclass`), sex, and age. The project also includes a detailed tutorial (PDF) on the theoretical background and implementation of Artificial Neural Networks (ANNs).

## 📚 Contents
- `titanic.py`: Python script to preprocess the dataset, build, train, and evaluate the ANN model.

## 🏗 Model Overview
- **Input Features**: `pclass`, `sex`, `age` (with missing values in `age` handled and all features normalized using Z-score normalization).
- **Neural Network Architecture**:
  - Input Layer: 3 neurons (one for each feature)
  - Hidden Layer: 10 neurons, ReLU activation
  - Output Layer: 1 neuron, Sigmoid activation
- **Loss Function**: Binary Crossentropy
- **Optimizer**: Adam
- **Evaluation**: Accuracy, Confusion Matrix, ROC Curve

## 🛠 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/titanic-ann.git
   cd titanic-ann
