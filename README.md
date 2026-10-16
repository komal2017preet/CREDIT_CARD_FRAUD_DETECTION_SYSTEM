# 🛡️ AEGIS GUARD AI — Credit Card Fraud Detection & Portfolio Platform

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.30%2B-FF4B4B.svg)](https://streamlit.io/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.3%2B-F7931E.svg)](https://scikit-learn.org/)
[![Plotly](https://img.shields.io/badge/Plotly-5.18%2B-3F4F75.svg)](https://plotly.com/)
[![Theme](https://img.shields.io/badge/UI%20Theme-Light%20Mode-brightgreen.svg)]()
[![Accuracy](https://img.shields.io/badge/Model%20Accuracy-99.95%25-blue.svg)]()

**AEGIS GUARD AI** is an enterprise-grade, portfolio-ready Machine Learning web application designed to detect fraudulent credit card transactions in real-time. Built with a clean **Light Mode Website Design System**, interactive line-navigation header, real-time risk scoring gauge, integrated Machine Learning theory, audit history logging, and dual ML algorithm benchmarking.

---

## ✨ Features & Navigation Sections

- **🏠 Home Page**: Website landing hero, platform KPI metric cards, core platform capabilities, **integrated Project & Domain Theory** (Financial Fraud context, Imbalanced Dataset dilemma, PCA anonymization, Ensemble solution), and developer portfolio spotlight card.
- **🎯 Fraud Predictor Engine**:
  - **Batch CSV Analysis**: Upload transaction CSV files, preview data, execute batch inference, filter by risk level, and download timestamped audit reports. Includes a **⚡ Load Demo Dataset** button for instant 1-click testing.
  - **Single Transaction Simulator**: Interactive parameter form with risk scenario templates (*Normal Retail Purchase*, *Midnight High-Risk Charge*, *Suspicious High-Amount Anomaly*), 0-100% risk score gauge, and decision status recommendations.
- **📊 Interactive Analytics Dashboard**:
  - Class Distribution Donut Chart (Genuine vs Fraud).
  - Log-scale Transaction Amount Boxplots & Histograms.
  - Interactive 2D & 3D Feature Space Scatter Plot for exploring spatial clusters between PCA features.
  - Key Feature Correlation Matrix Heatmap.
- **ℹ️ Models & About**:
  - Algorithm performance benchmark comparison matrix (Random Forest Ensemble ~99.95% accuracy vs Decision Tree ~99.92% accuracy).
  - **Integrated Algorithmic Theory & Financial Risk Matrix** (Gini Impurity, Bagging, Random Subspace Sampling, V14/V17 anomaly signals, Confusion Matrix trade-offs).
  - Developer profile and skill badges.
- **📜 Session Prediction History**: Timestamped audit logging, risk score filters, transaction search, and CSV export capabilities.

---

## 🏗️ Project Architecture

```
project of aiml/
├── app.py                     # Main Multi-Page Light Mode Streamlit Web Application
├── sample_creditcard.csv      # Lightweight Demo Dataset (150 rows) for 1-click testing
├── logistic_model.pkl         # Trained Random Forest Ensemble Model (99.95% acc)
├── decision_tree_model.pkl    # Trained Decision Tree Classifier Model (99.92% acc)
├── project.ipynb              # Jupyter Notebook (Model Training & EDA)
├── requirements.txt           # Project Dependencies
└── README.md                  # Project Documentation & User Guide
```

---

## ⚡ Quick Start Guide

### 1. Install Dependencies

```bash
pip install -r requirements.txt
```

### 2. Run the Streamlit Web Application

```bash
streamlit run app.py
```

Open your browser at `http://localhost:8501`.

---

## 📊 Machine Learning Model Benchmarks

| Metric | Random Forest (Ensemble) 🏆 | Decision Tree Classifier |
| :--- | :---: | :---: |
| **Accuracy** | **99.95%** | 99.92% |
| **Precision (Fraud)** | **94.2%** | 88.1% |
| **Recall (Fraud)** | **82.5%** | 78.4% |
| **F1-Score** | **88.0%** | 83.0% |
| **Inference Latency** | ~4ms / batch | ~1ms / batch |

---

## 🛠️ Built With

- **Python 3** — Core Programming Language
- **Streamlit** — Web Framework & Custom Light Mode Website System
- **Scikit-Learn** — Machine Learning Classifiers
- **Pandas & NumPy** — Data Manipulation & Vectorized Computation
- **Plotly** — Dynamic Interactive Data Visualizations
- **Joblib** — Model Serialization & Caching

---

## 👨‍💻 Developer & Portfolio Credits

Developed as a showcase AI/ML portfolio project for enterprise fraud analytics, real-time risk intelligence, and interactive ML educational concepts.
