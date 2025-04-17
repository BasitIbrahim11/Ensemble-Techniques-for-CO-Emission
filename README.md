# 🌍 CO₂ Emission Prediction using Ensemble Learning

This project focuses on predicting **carbon dioxide (CO₂) emissions** from vehicles using ensemble machine learning models. The aim is to build accurate regression models by combining multiple learners to capture complex relationships between features like engine size, fuel consumption, and emissions.

---

## 📁 Project Workflow

- **Outlier Detection & Removal**
- **Feature-Target Separation**
- **Encoding Categorical Features**
- **Standardization using StandardScaler**
- **Modeling Techniques:**
  - Random Forest Regressor
  - AdaBoost Regressor
  - Bagging Regressor (with Decision Tree)
  - Voting Regressor (combining multiple models)
- **Evaluation**:
  - Mean Squared Error (MSE)
  - R² Score

---

## 📊 Dataset Overview

- **Target Variable:** CO₂ Emissions (g/km)
- **Input Features:**  
  - Engine Size, Cylinders, Fuel Type, Fuel Consumption (City, Hwy, Comb), etc.
- **Source:** Government of Canada - Vehicle Emissions Dataset (Kaggle or Open Source)

---

## ✅ Key Findings

- **Voting Regressor** produced the most generalized results by combining outputs from multiple base models.
- Outlier removal and feature scaling significantly improved model performance.
- Feature importance is well captured by ensemble tree-based regressors.

---

## 🚀 Run this Notebook

You can open and run this notebook in Google Colab:

👉 [Open in Colab](https://colab.research.google.com/)  
→ Upload the file: `Ensemble_Techniques_for_CO2_Emission.ipynb`

---


## 👤 Author

- **Name:** Basit Ibrahim  
- **GitHub:** [github.com/yourusername](https://github.com/yourusername)  
- **Domain:** Machine Learning | Data Science | Regression Analysis

---

## 📚 License

This project is for academic and research purposes only.
