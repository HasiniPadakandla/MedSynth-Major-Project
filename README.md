# 🩺 MEDSYNTH: Predictive Analytics for Synthetic Patient Data

## 📘 Overview
**MEDSYNTH** is an AI-powered healthcare analytics system that predicts **multi-morbidity risk** (patients with more than two concurrent medical conditions) using health and demographic data.  
The project leverages **CTGAN-based synthetic data generation** to handle data scarcity, privacy, and imbalance issues while providing interpretable, real-time risk predictions through an interactive **Streamlit dashboard**.

---

## 🎯 Objectives
- Develop a predictive model to assess multi-morbidity risk using patient data.  
- Generate synthetic healthcare data using **CTGAN** to enhance model training and ensure privacy.  
- Implement **real-time prediction** and **batch processing** for scalable healthcare use.  
- Provide clear risk visualization and probability scoring for better clinical decisions.  

---

## ⚙️ Features
- 🧍 **Single-Patient Prediction Mode:** Real-time risk assessment with probability visualization.  
- 📂 **Batch Processing Mode:** Upload CSV files for population-level risk analysis.  
- 🧠 **Synthetic Data Generation:** Uses CTGAN to balance datasets and preserve patient privacy.  
- 📊 **Risk Visualization:** Color-coded risk categories and probability indicators.  
- 🩹 **Dual-Mode Deployment:** Supports both individual and institutional healthcare workflows.  

---

## 🧰 Tech Stack
**Programming Language:** Python  
**Libraries & Frameworks:**  
- Pandas, NumPy – Data handling and numerical computation  
- Scikit-learn – Model training and evaluation  
- CTGAN – Synthetic data generation  
- Streamlit – Dashboard interface  
- Matplotlib, Seaborn – Visualization  
- SciPy – Statistical testing and analysis  

---

## 🧪 Machine Learning Models Used
**Supervised Models:** Logistic Regression, Random Forest, Gradient Boosting  
**Unsupervised Models:** K-Means Clustering, PCA (Principal Component Analysis)

---

## 🧬 Why CTGAN?
CTGAN was used to overcome **data imbalance, scarcity, and privacy issues** in healthcare datasets.  
It generates **realistic synthetic patient data** that preserves statistical relationships, ensuring better model training and unbiased performance while protecting sensitive information.

---

## 🚀 Deployment
The project is deployed as a **Streamlit web application**, enabling users to:
- Input patient details or upload bulk data.  
- Instantly view risk predictions with probability scores and visual indicators.  

---

## 📊 Expected Outcomes
- Accurate, real-time prediction of multi-morbidity risks.  
- Privacy-preserving analytics using synthetic data.  
- Improved decision support for clinicians and healthcare institutions.  
- Scalable architecture for integration into existing healthcare systems.  

---

## 🔮 Future Scope
- Integration with **Electronic Health Records (EHR)** for real-time analysis.  
- Incorporate **deep learning models** for enhanced prediction accuracy.  
- Add **Explainable AI (XAI)** modules for better interpretability.  
- Support **IoT-based real-time health monitoring**.  
