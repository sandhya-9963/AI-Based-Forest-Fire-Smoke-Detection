# AI-Based-Forest-Fire-Smoke-Detection

# 🔥 AI-Based Forest Fire & Smoke Detection

## 📌 Project Overview
This project implements a machine learning-based system to detect forest fire and smoke regions using feature-level analysis from aerial imagery. The system supports drone-based disaster monitoring and early fire detection.

---

## 🎯 Objectives
- Detect fire and smoke regions using ML
- Analyze spatial fire risk
- Visualize fire-prone areas using heatmaps
- Support drone-based disaster response

---

## 📂 Dataset
The dataset consists of tile-level spectral, intensity, and texture features extracted from aerial imagery.

Target:
- `0` → No Fire/Smoke
- `1` → Fire/Smoke

---

## 🛠️ Technologies Used
- Python
- Jupyter Notebook
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn

---

## 🤖 Machine Learning Model
- Random Forest Classifier
- Feature Scaling using StandardScaler

---

## 📊 Model Evaluation
- Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC Curve

---

## 🌍 Spatial Risk Analysis
Fire risk probabilities are aggregated spatially and visualized using heatmaps to identify high-risk regions.

---

## 🚁 Drone Deployment Strategy
- Prioritize high-risk zones
- Use thermal sensors
- Enable real-time alerts

---

## 🚀 How to Run the Project
```bash
pip install -r requirements.txt
jupyter notebook
