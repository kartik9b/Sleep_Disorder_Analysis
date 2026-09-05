# Sleep_Disorder_Analysis

# 🌙 SomnoAnalytics: Sleep Health & Lifestyle AI Dashboard

An interactive, end-to-end Data Science and Machine Learning application designed to analyze personal sleep metrics, lifestyle factors, and cardiovascular health, while predicting individual risk levels for sleep disorders (**Insomnia** and **Sleep Apnea**) using a tuned **Random Forest Classifier**.

---

## 📌 Project Overview

Sleep disorders significantly impact global health, productivity, and overall well-being. This project provides a clinical analytics dashboard and dynamic predictive simulator powered by Machine Learning. 

### Key Highlights:
* **Exploratory Data Analytics (EDA):** Interactive multi-dimensional visualization of physiological markers (Blood Pressure, Heart Rate) and lifestyle habits (Physical Activity, Daily Steps, Stress Levels).
* **High-Accuracy ML Model:** Multi-class **Random Forest Classifier** trained and cross-validated with **96% validation accuracy**.
* **Modern Interactive Dashboard:** Sleek, dark-themed Streamlit UI built with **Plotly** graphics, dynamic filtering, and confidence score breakdowns.

---

## 🛠️ Tech Stack & Dependencies

* **Language:** Python 3.9+
* **Framework:** Streamlit
* **Data Processing & Analytics:** Pandas, NumPy
* **Data Visualization:** Plotly Express, Plotly Graph Objects, Seaborn, Matplotlib
* **Machine Learning:** Scikit-Learn (Random Forest, Train-Test-Split, Encoders)

---

## 📂 Repository Structure

```text
├── Sleep_disorder_data.csv          # Cleaned dataset containing patient sleep & lifestyle data
├── Sleep_Disorder_EDA_Model.ipynb   # Jupyter Notebook with full EDA, Feature Engineering & Model Evaluation
├── app.py                           # Main Streamlit Dashboard & ML Simulator Application
├── requirements.txt                 # Project dependencies for deployment
└── README.md                        # Project documentation
