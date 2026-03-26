# 🧪 ToxiScan – Drug Toxicity Predictor

## 🚀 Overview

ToxiScan is an AI-powered web application that predicts the toxicity of chemical compounds using machine learning and molecular analysis. It helps identify potentially harmful drug candidates early in the development process, reducing cost and improving safety.

---

## 🎯 Problem Statement

Drug development often fails due to unexpected toxicity in later stages. Detecting toxicity early can save time, cost, and human lives. This project uses AI to predict toxicity based on molecular structure.

---

## 💡 Solution

* Input: SMILES (chemical structure)
* Process: Feature extraction using molecular descriptors
* Output: Toxic / Non-Toxic prediction
* Additional: Explainability of results using feature importance

---

## 🧠 Features

* 🔍 Predict toxicity from SMILES input
* 🤖 Machine Learning model (XGBoost)
* 🧪 Molecular descriptor analysis
* 📊 Explainable AI using SHAP
* 🌐 User-friendly frontend (Kiro)
* ⚡ Fast backend using FastAPI

---

## 🛠️ Tech Stack
Frontend: Kiro
Backend: FastAPI
Machine Learning: XGBoost
Libraries: RDKit, SHAP, Scikit-learn
Language: Python, JavaScript
📸 Screenshots
🏠 Home Page
🔬 Prediction Page
🎥 Demo Video

👉 Click here to watch the demo:
🔗 https://www.kapwing.com/w/RBSMcLg30s

⚙️ How It Works
User enters a SMILES string
Backend extracts molecular features
ML model predicts toxicity
Result is displayed on UI
▶️ How to Run the Project
🔹 Backend
pip install -r requirements.txt
uvicorn app:app --reload
🔹 Frontend
Open index.html in your browser
📊 Dataset
Tox21 Dataset (Kaggle)
Contains chemical compounds and toxicity labels
🔮 Future Scope
Graph Neural Networks for better accuracy
Drug similarity analysis
Real-time API deployment
Advanced visualization of molecular structures
