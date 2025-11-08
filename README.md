# 🌐 Digital Habits and Mental Health  
### Exploring the Impact of Screen Time and Digital Behavior on Psychological Wellbeing 🤖  

A complete data science project examining how **digital lifestyles** affect **mental health** outcomes — including anxiety, depression, stress, happiness, and productivity.  
Includes a tabular dataset of **3,500 participants** with **24 research-inspired features**, plus a reproducible notebook for **EDA, feature engineering, modeling, and explainability**.

---

## 🧩 Project Overview

| Component | Description |
|:--|:--|
| **Dataset** | 24 variables covering demographics, digital activity, and mental health indicators. |
| **Notebook** | Full ML pipeline (EDA → Feature Engineering → Modeling → Explainability). |
| **Models** | Logistic Regression · Random Forest · XGBoost (GPU-ready). |
| **Goal** | Predict high mental-health risk from behavioral and psychological patterns. |

---

## 📊 Dataset Summary

| Metric | Value |
|:--|:--|
| Rows | **3,500** |
| Columns | **24** |
| Target | **high_risk_flag** |
| Type | Tabular (CSV) |

---

## 🧠 Feature Groups

### 🧬 Demographics  
Age · Gender · Region · Income Level · Education Level  

### 💻 Digital Behavior  
Daily Screen Time · Phone Unlocks · Notifications · Social Media Hours · Study Time  

### 🧘 Mental Health Indicators  
Anxiety · Depression · Stress · Happiness · Focus · Productivity  

### ⚠️ Risk Indicator  
`high_risk_flag` — a binary label derived via a **multi-factor wellbeing score** combining digital intensity, emotional state, and cognitive balance.

---

## 📘 Target Definition

The target variable **`high_risk_flag`** represents individuals with increased mental-health vulnerability.  
It is defined using a scoring rule that blends:  
- High digital activity (screen time, notifications, unlocks)  
- Elevated stress/anxiety levels  
- Lower happiness/focus scores  

Approximate distribution: **15–20% high-risk** to reflect population-level prevalence observed in behavioral research.

---

## 🚀 Quick Start

```bash
# Clone
git clone https://github.com/TarekMasryo/digital-habits-mental-health.git
cd digital-habits-mental-health

# (Optional) create venv
python -m venv .venv && source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the main notebook
jupyter notebook notebooks/predicting-wellbeing-risk.ipynb

```

---

## 🔬 Use Cases

- Predict mental-health risk from digital activity patterns.  
- Study correlation between digital dependence, stress, and sleep.  
- Build explainable AI models (SHAP/LIME) for behavioral insights.  
- Segment users by lifestyle balance and cognitive performance.  
- Reframe as regression tasks for continuous wellbeing indicators.

---
