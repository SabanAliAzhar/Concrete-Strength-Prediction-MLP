# Concrete-Strength-Prediction-MLP
Predict concrete compressive strength using a simple PyTorch MLP regression model based on material composition.

# Concrete Strength Prediction using MLP (PyTorch)

This project implements a **Multilayer Perceptron (MLP)** regression model using **PyTorch** to predict the **compressive strength of concrete** based on its material composition.

The model is trained on the **Concrete Compressive Strength Dataset**, where input features are standardized and fed into a neural network for supervised learning.

---

## 📂 Project Overview

- **Problem Type:** Regression  
- **Framework:** PyTorch  
- **Model:** Fully Connected Neural Network (MLP)  
- **Loss Function:** Mean Squared Error (MSE)  
- **Optimizer:** Adam  
- **Evaluation Metric:** RMSE (MPa)

---

## 🧠 Model Architecture

Input Layer (8 features)
↓
Fully Connected Layer (16 neurons)
↓
ReLU Activation
↓
Output Layer (1 neuron)


---

## 📊 Dataset

- **File:** `Concrete_Data.csv`
- **Features (8):**
  - Cement
  - Blast Furnace Slag
  - Fly Ash
  - Water
  - Superplasticizer
  - Coarse Aggregate
  - Fine Aggregate
  - Age
- **Target:**
  - Concrete Compressive Strength (MPa)

---

## ⚙️ Data Preprocessing

- Input features are **standardized** using `StandardScaler`
- Dataset is split into:
  - **80% Training**
  - **20% Testing**
- Data is converted to **PyTorch tensors**

---

## 🚀 Training Details

- **Epochs:** 300  
- **Learning Rate:** 0.01  
- **Batching:** Full-batch training  
- **Loss Tracking:** Training loss plotted over epochs

---

## 📈 Results

- Training and testing performance is evaluated using:
  - **Mean Squared Error (MSE)**
  - **Root Mean Squared Error (RMSE)**


