# 🔐 Network Intrusion Detection System (NIDS) using IBM Watsonx.ai

A machine learning-based system for detecting network intrusions by classifying traffic as either **normal** or **anomalous**. Built using IBM Watsonx.ai Studio with AutoAI for automated model training, selection, and deployment.

---

## 📌 Project Overview

This project leverages a **binary classification** model to distinguish between normal and malicious network traffic using historical data. It uses IBM Watsonx.ai AutoAI to automate feature preprocessing, model selection, hyperparameter tuning, and deployment.

---

## 🧠 Algorithm

- **Model Used**: Snap Decision Tree Classifier
- **Chosen By**: IBM Watsonx.ai AutoAI
- **Why Snap Decision Tree?**  
  - Fast training time  
  - High interpretability  
  - Optimized for binary classification on tabular data

---

## 📊 Input Features

The dataset includes a mix of **categorical** and **numerical** features:

- **Categorical**: `protocol_type`, `service`, `flag`
- **Numerical**: `src_bytes`, `dst_bytes`, `count`, `srv_count`, `serror_rate`, etc.
- **Target Variable**: `class` (`normal` or `anomaly`)

---

## ⚙️ Training Process

- Performed using **IBM AutoAI**
- Includes:
  - Automated feature engineering (scaling, encoding)
  - Cross-validation to ensure robustness
  - Hyperparameter tuning (HPO) for optimal performance

---

## 🚀 Prediction & Deployment

- The trained model is deployed on **IBM Cloud** using **Watson Machine Learning**
- Supports both **real-time and batch predictions**
- Each prediction outputs:
  - Class label (`normal` or `anomaly`)
  - Confidence score (probability)

---

## 📈 Future Scope

- Extend to **multiclass classification** for specific attack types (e.g., DoS, Probe)
- Integrate **real-time data streaming** from live networks
- Apply **deep learning models** for more complex traffic patterns
- Add **explainable AI (XAI)** for better interpretability
- Develop **dashboard and alert system** for non-technical users

---
# 🔐 Network Intrusion Detection System (NIDS) using IBM Watsonx.ai

A machine learning-based system for detecting network intrusions by classifying traffic as either **normal** or **anomalous**. Built using IBM Watsonx.ai Studio with AutoAI for automated model training, selection, and deployment.

---

## 📌 Project Overview

This project leverages a **binary classification** model to distinguish between normal and malicious network traffic using historical data. It uses IBM Watsonx.ai AutoAI to automate feature preprocessing, model selection, hyperparameter tuning, and deployment.

---

## 🧠 Algorithm

- **Model Used**: Snap Decision Tree Classifier
- **Chosen By**: IBM Watsonx.ai AutoAI
- **Why Snap Decision Tree?**  
  - Fast training time  
  - High interpretability  
  - Optimized for binary classification on tabular data

---

## 📊 Input Features

The dataset includes a mix of **categorical** and **numerical** features:

- **Categorical**: `protocol_type`, `service`, `flag`
- **Numerical**: `src_bytes`, `dst_bytes`, `count`, `srv_count`, `serror_rate`, etc.
- **Target Variable**: `class` (`normal` or `anomaly`)

---

## ⚙️ Training Process

- Performed using **IBM AutoAI**
- Includes:
  - Automated feature engineering (scaling, encoding)
  - Cross-validation to ensure robustness
  - Hyperparameter tuning (HPO) for optimal performance

---

## 🚀 Prediction & Deployment

- The trained model is deployed on **IBM Cloud** using **Watson Machine Learning**
- Supports both **real-time and batch predictions**
- Each prediction outputs:
  - Class label (`normal` or `anomaly`)
  - Confidence score (probability)

---

## 📈 Future Scope

- Extend to **multiclass classification** for specific attack types (e.g., DoS, Probe)
- Integrate **real-time data streaming** from live networks
- Apply **deep learning models** for more complex traffic patterns
- Add **explainable AI (XAI)** for better interpretability
- Develop **dashboard and alert system** for non-technical users

---

## 🙋‍♂️ Acknowledgements

- IBM SkillsBuild & Edunet Foundation  
- IBM Watsonx.ai Studio  
- Dataset: [NSL-KDD / Custom Kaggle Dataset]

