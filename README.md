# ✍️ Handwritten Digit Recognition

This project uses **Machine Learning** and **Computer Vision** techniques to recognize handwritten digits (0–9) from images using the **MNIST dataset**. The model is trained to accurately classify digits based on pixel patterns.

## 🔍 Project Overview

This notebook demonstrates:
- Loading and preprocessing the MNIST dataset
- Building and training a neural network using `TensorFlow` / `Keras`
- Evaluating the model's accuracy
- Predicting custom handwritten digits

## 🧠 Technologies Used

- Python 🐍
- Jupyter Notebook 📓
- TensorFlow / Keras 🤖
- NumPy & Matplotlib 📊
- scikit-learn 🧪

## 🗂️ Dataset

- **MNIST Dataset**: A large database of handwritten digits (60,000 training + 10,000 testing samples).
- Available directly via `keras.datasets`.

## 📈 Model Summary

- Input Layer: 784 neurons (28x28 pixel images)
- Hidden Layers: Dense layers with ReLU activation
- Output Layer: 10 neurons (0–9 digits) with Softmax activation
- Optimizer: Adam
- Loss: Categorical Crossentropy

## 📷 Output Examples

Here are a few digits and their predicted labels:

| Input Image | Prediction |
|-------------|------------|
|     3️⃣      |     3      |
|     7️⃣      |     7      |
|     1️⃣      |     1      |

<!--*(Add actual prediction visuals if available)*

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Handwritten_digit_Recognition.git
   cd Handwritten_digit_Recognition
   pip install -r requirements.txt
jupyter notebook Handwritten_digit_Recognition.ipynb

-->
