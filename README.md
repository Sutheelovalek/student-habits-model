
# 🎓 Student Habits Performance Model

A predictive web application built with [Streamlit](https://streamlit.io) that estimates a student's exam score based on study behavior and lifestyle factors.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue?logo=python" />
  <img src="https://img.shields.io/badge/Streamlit-app-success?logo=streamlit" />
  <img src="https://img.shields.io/github/license/Sutheelovalek/student-habits-model" />
</p>

---

## 🚀 Overview

This Streamlit app allows users to interactively adjust lifestyle factors and immediately see how they affect predicted exam performance.  
The model is trained using a dataset of student behavioral attributes and uses a pre-trained ML model saved in `best_model.pkl`.

---

## 🔍 Features

- Predicts **exam scores (0–100)** based on:
  - 📚 Study hours
  - 📈 Attendance %
  - 😌 Mental health (1–10)
  - 🛌 Sleep hours
  - 👔 Part-time job status
- Interactive sliders and dropdowns
- Model loading with `joblib`
- Prediction result with friendly UI

---

## 🧪 Demo (Local Preview)

### 🔧 1. Clone the Repository

```bash
git clone https://github.com/Sutheelovalek/student-habits-model.git
cd student-habits-model

