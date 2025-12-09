# Health_Insurance_Premium_Estimator_Application
Statistical ML Project to predict health insurance premiums

Models Used >  Linear Regression and XGBoost Regression

Data points used : Age, Genetic Risk , Weight Category , Smoking habbit , BMI , Exisiting Diseases if any..etc

This is deployed and available for try on Streamlit Hub

--------------------------------------------------------------------------------

<!-- PROJECT TITLE -->
<h1 align="center">🏥 Health Insurance Premium Estimator Application</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Deployment-Streamlit%20Cloud-brightgreen?style=for-the-badge" alt="Streamlit Cloud" />
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge" alt="Python" />
  <img src="https://img.shields.io/badge/Machine%20Learning-Regression-orange?style=for-the-badge" alt="ML" />
</p>

---

## 🌟 Live Demo (Streamlit Cloud)

<p align="center">
  <a href="https://healthinsurancepremiumestimatorapplication-aopysk9rnj2nzut23cu.streamlit.app/">
    <img src="https://img.shields.io/badge/🌐%20Open%20Live%20App-Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Live Demo" />
  </a>
</p>

Experience the application online!  
➡️ **Click the button above to open the fully deployed app on Streamlit Cloud.**

---

## 🔍 Project Overview

This repository contains a **Health Insurance Premium Estimator** that predicts estimated premium cost based on user inputs such as age, BMI, region, smoker status, and other health-related factors.

The project includes:

- 🧠 A trained **machine learning model**
- 🧪 Data preprocessing utilities
- 🖥️ A **Streamlit web app** for user interaction
- 📦 Deployment-ready structure
- 📄 Editable and extendable ML pipeline

---

## 🛠️ Technologies & Libraries Used

### **Languages**
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="60" alt="Python" />
</p>

### **Frameworks & Tools**
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/streamlit/streamlit-original.svg" width="55" alt="Streamlit" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="55" alt="Git" />
</p>

### **Libraries**
<p align="left">
  <img src="https://pandas.pydata.org/static/img/pandas_secondary.svg" width="95" alt="Pandas" />
  <img src="https://numpy.org/images/logo.svg" width="85" alt="NumPy" />
  <img src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width="90" alt="scikit-learn" />
  <img src="https://www.svgrepo.com/show/353945/joblib.svg" width="70" alt="Joblib" />
</p>

---

## 📁 Repository Structure

```text
Health_Insurance_Premium_Estimator_Application/
│
├── app/
│   ├── main.py                  # Streamlit application
│   ├── prediction_helper.py     # ML prediction + preprocessing logic
│   └── model/
│       └── model.joblib         # Trained model file (example name)
│
├── data/
│   └── insurance.csv            # Dataset used for training
│
├── requirements.txt             # Dependencies
├── notebook.ipynb               # Training or EDA notebook
└── README.md                    # Documentation
