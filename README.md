# CarInsuranceFraudDetection
A machine learning project focused on car insurance fraud detection.  It applies EDA, data balancing with SMOTE, and models like Random Forest to improve accuracy and fairness in fraud classification.
# Insurance Fraud Detection 🚗💥

This project focuses on **detecting car insurance fraud claims** using 
machine learning techniques. Fraudulent claims are a critical issue in 
the insurance industry, leading to significant financial losses. 
The goal is to build a reliable model to classify claims as **fraudulent** 
or **genuine**.

---

## 📂 Project Overview
- **Dataset**: Car insurance claims dataset  
- **Target Variable**: `FraudFound_P` (1 = Fraud, 0 = Genuine)  
- **Key Features**: Claim details, vehicle information, policy details, 
  driver information, etc.  
- **Techniques Used**:  
  - Exploratory Data Analysis (EDA)  
  - Feature Engineering  
  - Handling imbalanced data using **SMOTE**  
  - Model training with **Random Forest**, **Lazy Predict**, etc.  
  - Evaluation with Accuracy, Balanced Accuracy, ROC-AUC, F1-Score  

---

## ⚙️ Tech Stack
- Python 🐍  
- Pandas, NumPy  
- Scikit-learn  
- LazyPredict  
- Imbalanced-learn (SMOTE)  
- Matplotlib / Seaborn  

---

## 📊 Results
- **Random Forest** achieved high ROC-AUC and F1-score after applying SMOTE.  
- Balanced Accuracy improved significantly from ~0.50 to ~0.97.  
- ROC-AUC reached ~0.99 after balancing.  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/InsuranceFraudML.git
