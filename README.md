#  Churn Prediction for ConnectSphere Telecom

## Problem Statement

Customer retention is critical in the telecom industry. This project aims to predict whether a customer is likely to churn using demographic, service, and billing data. Early identification allows companies like **ConnectSphere** to take proactive steps to reduce churn.

---

## Dataset  
- **Rows**: ~7000  
- **Target**: `Churn` (Yes/No)  
- Features: Customer demographics, contract type, internet/billing issues, tenure, charges, etc.

---

## Model

A simple **Artificial Neural Network (ANN)** using Keras:

- Input Layer: All features after encoding
- Hidden Layers: 2 (ReLU activation)
- Output Layer: 1 neuron (Sigmoid for binary classification)
- Loss Function: Binary Crossentropy
- Optimizer: Adam
- Epochs: 50

---

## Results

- Accuracy: ~80–85%
- Recall: Balanced
- Classification report & confusion matrix
- Training history visualization

---

## Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- TensorFlow / Keras
- Google Colab

---

