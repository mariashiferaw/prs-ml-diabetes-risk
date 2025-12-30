# 🧬 PRS-ML Diabetes Risk — Polygenic Risk Score + Machine Learning Prediction

**Goal:** Build a predictive model that estimates Type 2 Diabetes risk by integrating **Polygenic Risk Scores (PRS)** with **Machine Learning** using genomic, clinical, and lifestyle data.

This project demonstrates the use of genomics-based risk scores combined with advanced ML algorithms to improve accuracy beyond traditional PRS linear models.

---

## 📁 Repository Contents
| File | Description |
|------|-------------|
| `Shiferaw_ResearchProposal.docx` | Full research proposal outlining PRS-ML methodology, workflow, datasets, and timeline |
| `AI_PolygenicRiskScores_Genomics.docx` | Literature review summarizing genomics + AI research and foundations for ML model |

*(Notebook files and code will be added soon — Python implementation, dataset pipeline, SHAP plots, etc.)*

---

## 🧠 What the Model Does
✔ Calculates PRS using SNP-based genomic variants  
✔ Integrates clinical & lifestyle variables  
✔ Trains ML models (Random Forest, Gradient Boosting, Neural Network)  
✔ Evaluates using AUC, precision, recall, and F1-score  
✔ Uses **SHAP for explainability** — identifies most influential genetic markers  

---

## 🧪 Planned ML Pipeline (Python)
```python
PRS → Feature Engineering → Train/Test Split → RandomForestClassifier() → SHAP Explainability → AUC Evaluation
