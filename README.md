# 🌱 Analysis on Pesticide Poisoning — AI Diagnosis System

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)

**An AI-powered diagnosis pipeline for pesticide poisoning detection in rural workers — achieving 98% accuracy using the DRC-SML algorithm.**

</div>

---

## 📌 Problem Statement

Pesticide poisoning is a **critical public health crisis** in rural India, affecting millions of agricultural workers annually. Delayed or incorrect diagnosis can be fatal. Existing diagnostic methods are expensive and unavailable in remote areas.

This project builds a complete AI data science pipeline that can accurately detect pesticide poisoning from clinical sample data — enabling timely, affordable diagnosis for rural communities.

---

## 🎯 Results

| Metric | Score |
|--------|-------|
| ✅ Accuracy | **98%** |
| 📊 Sample Size | 1,027 clinical samples |
| 📈 Precision | 97.4% |
| 🔷 Recall | 98.2% |
| ⚡ Algorithm | DRC-SML (Dynamic Rule-based Classification with Supervised ML) |

---

## 🧠 Pipeline Architecture

```
Clinical Samples (1,027)
        ↓
   Data Collection & Labeling
        ↓
   Preprocessing & Feature Engineering
        ↓
   DRC-SML Algorithm
   (Dynamic Rule Classification + Supervised ML)
        ↓
   Model Evaluation (98% Accuracy)
        ↓
   Diagnosis Output → Poisoning Type & Severity
```

---

## 🔬 About the DRC-SML Algorithm

The **DRC-SML (Dynamic Rule-based Classification with Supervised Machine Learning)** algorithm combines:

- **Rule-based classification** — expert medical rules for initial filtering
- **Supervised ML** — trained on labeled clinical data for final prediction
- **Dynamic thresholding** — adapts to varying symptom patterns

This hybrid approach outperforms standard ML models on small clinical datasets.

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| Language | Python 3.8+ |
| ML Pipeline | Scikit-learn |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Algorithm | DRC-SML (custom hybrid) |
| Notebook | Jupyter Notebook |

---

## 📂 Project Structure

```
Analysis-on-pesticides-poisoning/
│
├── 📓 pesticide_analysis.ipynb     # Full pipeline notebook
├── 🐍 drc_sml.py                   # Custom DRC-SML algorithm
├── 📊 data/
│   └── pesticide_samples.csv       # 1,027 clinical samples
├── 📈 results/
│   ├── confusion_matrix.png
│   └── accuracy_report.txt
├── 📋 requirements.txt
└── 📖 README.md
```

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/shiav321/Analysis-on-pesticides-poisoning-.git
cd Analysis-on-pesticides-poisoning-

# 2. Install dependencies
pip install -r requirements.txt

# 3. Open notebook
jupyter notebook pesticide_analysis.ipynb
```

---

## 🌍 Social Impact

- 🏥 Enables diagnosis in **remote rural clinics** without specialist doctors
- ⚡ Reduces diagnosis time from hours to **seconds**
- 💰 Dramatically cuts diagnostic costs for low-income farmers
- 🌾 Directly improves **quality of life** for agricultural workers in India
- 📱 Scalable to mobile app deployment for field workers

---

## 📊 Dataset Details

| Property | Value |
|----------|-------|
| Total Samples | 1,027 |
| Features | 15 clinical indicators |
| Classes | Poisoning Type (4 categories) |
| Source | Clinical data collection |
| Balance | Stratified split applied |

---

## 👨‍💻 About the Developer

**Shiva Keshava** — B.Tech AI & Data Science Graduate

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/shiva-keshava-b71355364)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-FF6B6B?style=flat&logo=google-chrome)](https://shivaprofilewebsite.lovable.app/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat&logo=github)](https://github.com/shiav321)

---

<div align="center">

**This project was developed as a final year B.Tech project at Annamacharya Institute of Technology & Sciences**

⭐ Star this repo if you believe in accessible healthcare through AI!

</div>

