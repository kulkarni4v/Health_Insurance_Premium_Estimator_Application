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
  <img src="https://img.shields.io/badge/Model-Machine%20Learning-orange?style=for-the-badge" alt="ML" />
</p>

---

## 🌟 Live Demo

<p align="center">
  <a href="https://<your-streamlit-app-link>">
    <img src="https://img.shields.io/badge/🌐%20Open%20Live%20App-Streamlit-red?style=for-the-badge&logo=streamlit&logoColor=white" alt="Open Live App" />
  </a>
</p>

> _Replace `[<your-streamlit-app-link>](https://healthinsurancepremiumestimatorapplication-aopysk9rnj2nzut23cu.streamlit.app/)` with the actual app URL once deployed._

---

## 🔍 Project Overview

This repository implements a **Health Insurance Premium Estimator**, which predicts estimated insurance premiums based on user health and demographic data.  
It includes:

- 🧠 A trained **machine-learning model**  
- 🧪 Code for **data preprocessing**  
- 🖥️ A **Streamlit web-app frontend** for user interaction  
- 📄 (Optional) Notebook or code used for training  
- 📥 Instructions for running locally or deploying  

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

</p>

---

## 📁 Repository Structure

```text
Health_Insurance_Premium_Estimator_Application/
│
├── requirements.txt             # Python dependencies
├── app/                         # Web app package (or root streamlit script)
│   └── main.py (or app.py)      # Streamlit application entry point
│
├── model/                       # (or artifacts/) model files
│   └── <trained_model>.joblib   # Serialized ML model object
│
├── preprocessing/               # (optional) data preprocessing utilities
│   └── <helper_scripts>.py      
│
├── notebook/                    # (optional) exploratory / training notebooks
│   └── *.ipynb                  
│
└── README.md                    # This file

