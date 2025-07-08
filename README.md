# ✈️ Airline Passenger Satisfaction Predictor – Deep Learning Web App

An end-to-end machine learning & deep learning solution designed to predict airline passenger satisfaction using flight experience data. This project brings together **PyTorch**, best practices in data science, and a clean **Streamlit UI** for real-time interaction, deployed seamlessly on **Hugging Face Spaces**.

---

## 📌 1. Project Description and Goals

### 🔍 Overview  
This project focuses on predicting a passenger's satisfaction status (**Satisfied** or **Neutral/Dissatisfied**) based on various flight experience factors such as inflight service, class, delay status, and more.

### 🎯 Goals
- **Prediction** – Accurately predict passenger satisfaction using a deep learning model.  
- **Insights** – Identify factors contributing to dissatisfaction, helping airlines enhance customer experience.

---

## 🧩 2. Workflow / Methodology

### 🔄 Project Flow
- Data Collection (Kaggle)  
- Exploratory Data Analysis (EDA)  
- Data Preprocessing & Feature Engineering  
- Model Building: ML Models + Artificial Neural Networks (ANN)  
- Hyperparameter Tuning & Evaluation  
- Streamlit UI Development  
- Deployment on Hugging Face Spaces  

### 📊 Data
- **Source**: [Kaggle – Airline Passenger Satisfaction](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)  
- **Size**: ~130,000 records with 23 columns  
- **Target Variable**: `Satisfaction` (Satisfied / Neutral or Dissatisfied)  
- **Split**: 80% Training / 20% Testing  

### 🧠 Model Development
- Trained and evaluated multiple binary classification ML models (Logistic Regression, Random Forest, etc.)  
- Transitioned to **ANN using PyTorch** after ML models underperformed  
- Developed 3 ANN variations with different hyperparameters  
- Final ANN selected based on:
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
Dataset sourced directly from Kaggle. Includes both demographic & flight-specific features.

### 🧹 Data Preprocessing  
- Handled missing values  
- Encoded categorical variables  
- Standardized numerical features  
- Addressed class imbalance (if any)  

### 🧠 Model Training  
- Implemented ANN with PyTorch  
- Used ReLU activations, dropout regularization, and Adam optimizer  
- Performed batch training with evaluation on each epoch  

### 🔧 Parameter Tuning  
- Tuned hyperparameters: hidden layers, neurons, learning rate, batch size  
- Evaluated improvements across ANN variants  

### 🚀 Deployment  
- Developed a responsive, interactive frontend with **Streamlit**  
- Deployed publicly on **Hugging Face Spaces**  

---

## 📊 4. Results and Discussion

| Metric    | Value |
|-----------|-------|
| Accuracy  | 96%   |
| Precision | 96%   |
| Recall    | 94%   |
| F1-Score  | 95%   |

### 💬 Discussion
- The ANN model significantly outperformed classical ML models.  
- It performs well in identifying both satisfied and dissatisfied passengers.  
- Provides a scalable solution for airline companies to better understand customer sentiment.

---

## 🏁 5. Conclusion

This project successfully demonstrates an end-to-end deployment of a deep learning classifier with a usable web interface.  
It can help airline companies:

- Understand what affects passenger satisfaction  
- Make data-driven service improvements  
- Deploy AI-driven interactive solutions using open-source tools  

---

## 🌐 Live Demo & Project Files

🔗 **Try the App on Hugging Face**:  
[https://huggingface.co/spaces/rohithmasineni/airline-passenger-satisfaction-predictor](https://huggingface.co/spaces/rohithmasineni/airline-passenger-satisfaction-predictor)

📁 **All Streamlit-related files used in the app (including model, preprocessing script, and app code) are available in the Hugging Face repository**:  
[https://huggingface.co/spaces/rohithmasineni/airline-passenger-satisfaction-predictor/tree/main/src](https://huggingface.co/spaces/rohithmasineni/airline-passenger-satisfaction-predictor/tree/main/src)

---

## 📬 Contact

Feel free to explore the code and resources provided in the uploaded files.  
If you have any **feedback, suggestions, or ideas for improvement**, I’d love to hear from you!

- 📧 **Email**: rohithmasineni223@email.com  
- 🔗 **LinkedIn**: [Rohith Kumar Masineni](https://www.linkedin.com/in/rohith-kumar-masineni/)

---

⭐ **If you found this project useful, feel free to star the repository!**
