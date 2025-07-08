# Airline-Passenger-Satisfaction-Predictor

# ✈️ Airline Passenger Satisfaction Predictor – Deep Learning Web App

An end-to-end machine learning & deep learning solution designed to predict airline passenger satisfaction using flight experience data. This project combines the power of PyTorch, data science best practices, and Streamlit UI for real-time interaction, deployed seamlessly on Hugging Face Spaces.

---

## 📌 1. Project Description and Goals

### 🔍 Overview
This project focuses on predicting a passenger's satisfaction status (`Satisfied` or `Neutral/Dissatisfied`) based on various flight experience factors such as inflight service, class, delay status, and more.

### 🎯 Goal
The goal is two-fold:
1. **Prediction** – Accurately predict passenger satisfaction using a deep learning model.
2. **Insights** – Identify what factors contribute to dissatisfaction, helping airlines enhance customer experience by targeting specific areas for improvement.

---

## 🧩 2. Workflow / Methodology

### 🔄 Project Flow
1. Data Collection (Kaggle)
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing & Feature Engineering
4. Model Building: ML models + Artificial Neural Networks (ANN)
5. Hyperparameter Tuning & Evaluation
6. Streamlit UI Development
7. Deployment on Hugging Face Spaces

### 📊 Data
- **Source**: [Kaggle – Airline Passenger Satisfaction](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)
- **Size**: ~130,000 records with 23 columns
- **Target Variable**: `Satisfaction` (Satisfied / Neutral or Dissatisfied)
- **Split**: 80% Training / 20% Testing

### 🧠 Model Development
- Trained and evaluated multiple **binary classification ML models** (Logistic Regression, Random Forest, etc.)
- Transitioned to **ANN (PyTorch)** after ML models underperformed
- Developed 3 ANN variations with different hyperparameters
- Selected the best-performing ANN model based on:
  - Accuracy
  - Precision/Recall Balance
  - Training Time
  - Inference Efficiency

### 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Curve

---

## ⚙️ 3. Detailed Steps

### 📥 Data Collection
- Dataset sourced directly from Kaggle.
- Includes both demographic & flight-specific features.

### 🧹 Data Preprocessing
- Handled missing values with appropriate strategies
- Encoded categorical variables
- Standardized numerical features
- Addressed class imbalance (if any)

### 🧠 Model Training
- Used **PyTorch** to implement ANN architecture
- ReLU activations, dropout regularization, and appropriate optimizers (Adam, etc.)
- Batch training with evaluation per epoch

### 🔧 Parameter Tuning
- Adjusted number of hidden layers, neurons, learning rate, batch size
- Validated model improvements across ANN versions

### 🚀 Deployment
- Built Streamlit-based frontend for prediction and UI experience
- Deployed on **Hugging Face Spaces** for public access

### 4. Results and Discussion
| Metric    | Value |
| --------- | ----- |
| Accuracy  | 91.2% |
| Precision | 90.5% |
| Recall    | 92.0% |
| F1-Score  | 91.2% |

### 💬 Discussion
The ANN model significantly outperformed classical ML models in prediction accuracy and generalization.

The model performs well in identifying both satisfied and dissatisfied passengers.

### 6. Conclusion
This project successfully demonstrates an end-to-end deployment of a deep learning classifier with a usable web interface. The model can be leveraged by airline companies to:

Understand what affects passenger satisfaction

Take data-driven decisions to improve service

Deploy scalable, interactive solutions using open-source tools

### 🌐 Live Demo & Link: 
Try the App on Hugging Face

#### Contact
For feedback, suggestions, or collaborations:

📧 rohithmasineni223@email.com

🔗 Connect with me on LinkedIn:

