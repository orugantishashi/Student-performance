# 🎓 Student Performance Intel: AI-Driven Analytics & Prediction

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Streamlit](https://img.shields.io/badge/Framework-Streamlit-red)
![Scikit-Learn](https://img.shields.io/badge/ML-Scikit--Learn-orange)
![TensorFlow](https://img.shields.io/badge/DeepLearning-TensorFlow-orange)

A high-performance Machine Learning & Deep Learning system designed to analyze, classify, and predict student academic success using advanced data analytics techniques.

---

## 📑 Project Abstract

Predicting student performance is a critical task for educational institutions to provide timely academic support and improve learning outcomes.

This project implements a comprehensive Machine Learning and Deep Learning pipeline to categorize student academic performance into three categories:

* ❌ Fail
* ✅ Pass
* 🏆 Distinction

By analyzing demographic, social, lifestyle, and academic indicators such as study habits, parental background, attendance, and previous grades, the system generates meaningful predictions and actionable insights.

The platform combines:

* Supervised Learning for prediction
* Unsupervised Learning for clustering
* Dimensionality Reduction for pattern discovery
* Interactive Data Visualization for decision-making

All insights are delivered through a modern and interactive Streamlit Dashboard.

---

# ✨ Key Features

## 🕵️ Intelligent Data Analysis & Visualization

* Correlation Heatmaps to identify relationships between factors affecting student performance.
* Interactive Visualizations using Plotly.
* Grade Distribution Analysis.
* Student Demographics Insights.
* Real-time Dataset Statistics Dashboard.

---

## 🤖 Multi-Model Prediction Engine

The system evaluates multiple machine learning algorithms and selects the best-performing model.

### Implemented Models

* Random Forest Classifier ⭐
* Support Vector Machine (SVM)
* Logistic Regression
* Decision Tree Classifier

### Prediction Output

* Fail
* Pass
* Distinction

---

## 🧠 Deep Learning Integration

### Artificial Neural Network (ANN)

A custom Multi-Layer Perceptron (MLP) built using TensorFlow/Keras to capture complex non-linear relationships within student academic data.

Capabilities:

* Deep Pattern Recognition
* Improved Learning Representation
* Enhanced Predictive Insights

---

## 🌀 Unsupervised Learning Insights

### Principal Component Analysis (PCA)

Used for dimensionality reduction and visualization of high-dimensional student data.

Benefits:

* Better pattern understanding
* Reduced feature complexity
* 2D and 3D data exploration

### K-Means Clustering

Students are grouped into unique academic personas based on behavioral and performance patterns.

Examples:

* High Performers
* Consistent Learners
* At-Risk Students
* Improvement Candidates

---

# 📊 Dashboard Features

The Streamlit Dashboard provides:

### 📈 Analytics

* Performance Trends
* Academic Insights
* Correlation Analysis

### 🎯 Predictions

* Individual Student Prediction
* Real-time Result Classification
* Confidence Analysis

### 📉 Visualizations

* Histograms
* Pie Charts
* Scatter Plots
* Heatmaps
* Cluster Visualizations

### 🧩 Clustering View

* Student Segmentation
* Academic Persona Identification
* Behavioral Pattern Recognition

---

# 🛠️ Tech Stack & Architecture

| Category             | Technology                  |
| -------------------- | --------------------------- |
| Programming Language | Python                      |
| Framework            | Streamlit                   |
| Machine Learning     | Scikit-Learn                |
| Deep Learning        | TensorFlow / Keras          |
| Data Processing      | Pandas, NumPy               |
| Visualization        | Matplotlib, Seaborn, Plotly |

# 📁 Project Architecture

```bash
MACHINE-LEARNING-PROJECT/
│
├── data/
│   └── student_data.csv
│
├── models/
│   ├── random_forest.pkl
│   ├── svm_model.pkl
│   ├── logistic_model.pkl
│   └── ann_model.h5
│
├── visualizations/
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   └── clustering_results.png
│
├── app.py
├── train_model.py
├── run_project.bat
├── requirements.txt
└── walkthrough.md


# 🚀 Installation & Setup

## Prerequisites

* Python 3.8+
* Git
* Pip


## Quick Start

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Train Models

```bash
python train_model.py
```

### Launch Dashboard

```bash
streamlit run app.py
```

---

# 📊 Model Performance

| Algorithm            | Accuracy | Verdict          |
| -------------------- | -------- | ---------------- |
| Random Forest        | ~90%     | ✅ Best Performer |
| SVM                  | ~88%     | ✅ Reliable       |
| Neural Network (ANN) | ~85%     | ✅ Strong         |
| Logistic Regression  | ~82%     | ℹ️ Baseline      |

> Note: Results may vary depending on dataset quality, hyperparameter tuning, and train-test split ratio.

---

# 🎯 Project Objectives

* Predict student academic performance.
* Identify students needing academic support.
* Discover hidden behavioral patterns.
* Improve educational decision-making.
* Enable data-driven student mentoring.

---

# 👨‍💻 Team Members & Responsibilities

### Shashi Kumar (Team Lead)

* Machine Learning Model Development
* Random Forest, SVM & ANN Implementation
* K-Means Clustering & PCA
* Model Training & Evaluation

### Yashwanth Punna

* Data Collection & Dataset Preparation
* Data Cleaning & Preprocessing
* Feature Engineering

### Venkatesh Benjarapu

* Streamlit Dashboard Development
* Frontend Design
* User Interface Development

### Yenna Gnaneshwar

* Data Visualization & Analytics
* Plotly, Seaborn & Matplotlib Integration
* Insight Generation

### Sudheendra

* Testing & Validation
* Documentation
* Deployment & Presentation Support

---

# 🙏 Acknowledgments

We express our sincere gratitude to our faculty mentors, department staff, and Aurora Deemed to be University for their guidance, encouragement, and continuous support throughout the development of this project.

---

## ❤️ Developed With Passion

**Student Performance Intel: AI-Driven Analytics & Prediction**

Developed by:

**Shashi Kumar • Yashwanth Punna • Venkatesh Benjarapu • Yenna Gnaneshwar • Sudheendra**

🏫 Aurora Deemed to be University
