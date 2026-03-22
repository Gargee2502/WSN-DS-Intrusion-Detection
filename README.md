# Optuna-Optimized XGBoost for Intrusion Detection in WSNs

## Overview
This project presents a machine learning-based Intrusion Detection System (IDS) for Wireless Sensor Networks (WSNs).  
It leverages **Optuna for hyperparameter optimization** and **SMOTE for handling class imbalance** to significantly improve detection performance.
The system is evaluated on the **WSN-DS dataset** and compared with traditional models such as Random Forest, Linear SVM, and Naïve Bayes.

---

## Key Features
- Detects multiple WSN attacks:
  - Blackhole
  - Grayhole
  - Flooding
  - TDMA (Scheduling)
- Optuna-based hyperparameter optimization
- SMOTE for class imbalance handling
- Comparative analysis with multiple ML models
- High performance with:
  - **Accuracy > 99%**
  - **Macro AUROC: 0.9985**

---

## Tech Stack
- Python
- Scikit-learn
- XGBoost
- Optuna
- Pandas, NumPy
- Matplotlib / Seaborn

---

##  Project Structure
├── wsn_research.py # Main implementation
├── Article for WSN DS.pdf # Research paper
├── README.md # Documentation

Author: Gargee Rai
