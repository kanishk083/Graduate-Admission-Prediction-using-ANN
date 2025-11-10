# 🎓 Graduate Admission Prediction using ANN

A machine learning project that predicts the likelihood of a student’s graduate school admission based on academic and test performance metrics — built using **NumPy**, **Pandas**, **Keras**, and **Scikit-learn**.

This project demonstrates how **Artificial Neural Networks (ANNs)** can be applied to **regression problems** for predictive analytics in education.

---

## 🧠 Project Overview

The goal is to predict the **chance of admission** (ranging from 0 to 1) for students applying to graduate programs using their profile data such as:
- GRE Score  
- TOEFL Score  
- University Rating  
- Statement of Purpose (SOP) Strength  
- Letter of Recommendation (LOR) Strength  
- Undergraduate GPA (CGPA)  
- Research Experience  

We use a **fully connected feed-forward neural network** trained on the **Graduate Admissions dataset**.

---

## 🧩 Technologies Used

- **Python 3.x**
- **NumPy** → numerical computations  
- **Pandas** → data handling and preprocessing  
- **Scikit-learn** → data scaling, splitting, and evaluation metrics  
- **Keras (TensorFlow backend)** → building and training the ANN model  

---

## ⚙️ Workflow

1. **Data Preprocessing**
   - Load dataset using Pandas  
   - Handle missing or duplicate data  
   - Normalize input features using `StandardScaler`  

2. **Model Architecture**
   - Input layer with 7 input features  
   - 2 hidden layers with ReLU activation  
   - Output layer with linear activation (for regression output)  

3. **Training**
   - Optimizer: `adam`  
   - Loss function: `mean_squared_error`  
   - Evaluation metric: `r2_score`  

4. **Evaluation**
   - Split data into train and test sets  
   - Plot training and validation loss curves  
   - Compare predicted vs actual admission chances  

---


