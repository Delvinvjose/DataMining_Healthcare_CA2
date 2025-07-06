# Predicting Healthcare Test Outcomes | Data Mining CA2 (DBS)

📊 **Module:** B9DA110 Data and Network Mining  
🎓 **Course:** MSc in Data Analytics  
🏫 **Institution:** Dublin Business School (DBS), Ireland  
📅 **Academic Year:** 2024–2025

---

## 📂 Folder Structure

| Folder | Description |
|--------|-------------|
| **automodel/** | Contains `automodel.csv` — benchmark results for automated model runs. |
| **code/** | Final Python scripts (`datamining_ca_2.py`) for Decision Tree, Random Forest, Logistic Regression (with tuning). Includes `pdf_code.pdf` for reference. |
| **dataset/** | `healthcare_dataset.csv` from Kaggle: 55k+ patient records with test results. |
| **presenation/** | Group presentation slides in `.pptx` and `.odp` formats. |
| **report/** | `Final Report.pdf` covering business understanding, CRISP-DM stages, results, and deployment plan. |

---

## 📑 Project Overview

This project predicts whether a patient’s healthcare test result will be **“Normal”** or **“Abnormal”** using real hospital data and machine learning.  
It compares multiple algorithms and shows how data preprocessing and hyperparameter tuning improve model performance for healthcare applications.

---

## 🏥 Models Used

- ✅ Decision Tree (Basic & Tuned)
- ✅ Random Forest (Basic & Tuned)
- ✅ Logistic Regression (Basic & Tuned)
- ✅ Benchmarked with `automodel.csv` baseline

**Best model:** Tuned Random Forest — balanced precision, recall, F1-Score.

---

## ⚙️ Techniques

- Encoding, StandardScaler
- SMOTE for class balancing
- GridSearchCV for tuning
- LIME for interpretability
- ROC/AUC, Confusion Matrix, Feature Importance

---

## 🚀 Deployment Plan

- Tuned RF model can be deployed as API or integrated into EHR systems.
- Use SHAP or LIME for local explainability.
- Monitor and retrain with feedback loops.

---

## ✏️ Team Members

- **Delvin Vallooran Jose (20047713)**
- **Muhammed Mukhsith Thekke Mattara (20040105)**
- **Eldhose Thelakkattu Benny (20044108)**

---

## ⚖️ License

For educational & non-commercial use only.
