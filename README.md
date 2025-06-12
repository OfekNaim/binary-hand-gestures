# Binary Image Classification with Neural Network (NumPy)

This project was completed as part of the **"Basics of Deep Learning"** course at Colman College, 2024.

We implemented a feedforward neural network from scratch using NumPy to classify grayscale images of hand-sign digits (only digits 2 and 7) from a custom dataset. This assignment included designing the model architecture, implementing forward and backward propagation, and training the model using binary cross-entropy loss.

## 👨‍💻 Authors
- Ofek Naim  
- Hinoy Solomon

## 📊 Dataset
- Hand sign digit images (grayscale 28x28 pixels).
- Subset of 1000 images containing only digits 2 and 7.
- Data was flattened and normalized to values between 0 and 1.
- 80% training, 20% testing split.

## 🧠 Model Architecture
- Input layer: 784 neurons (flattened 28x28 images)
- 3 hidden layers: 128 neurons each, sigmoid activation
- Output layer: 1 neuron (binary classification)
- Loss: Binary Cross-Entropy (BCE)
- Optimizer: Gradient Descent

## 📈 Results
- **Accuracy**: 99.9999% on test set
- **Confusion Matrix**:

  | Actual \ Predicted | 2 | 7 |
  |--------------------|---|---|
  | 2                  | 100 | 0 |
  | 7                  | 0   | 100 |


## 📁 Files
- `binary-hand-gestures.ipynb` – Jupyter Notebook with full implementation
- `report.pdf` – Project documentation and discussion
- `README.md`
