# 🚗 Motor Vehicle Insurance — Exploratory Data Analysis

An end-to-end EDA on a real-world motor vehicle insurance dataset (~105,000 policy records) sourced from Mendeley. The goal is to uncover patterns in premiums, claims behaviour, and vehicle characteristics that drive insurance risk.

---

## 📌 Project Overview

| Detail | Info |
|--------|------|
| **Dataset** | Motor Vehicle Insurance Data (Mendeley) |
| **Records** | ~105,000 policy records |
| **Tools** | Python · pandas · matplotlib · seaborn |
| **Notebook** | `Insurance_EDA_Template.ipynb` |

---

## 🔍 What's Covered

| Step | Analysis |
|------|----------|
| 1–3 | Library setup, data loading, structure inspection |
| 4–5 | Missing value audit & summary statistics |
| 6 | Premium distribution (histogram + boxplot) |
| 7 | Claims breakdown — rate and pie chart |
| 8 | Premium vs. claims cost scatter + correlation |
| 9 | Vehicle age distribution & age category bucketing |
| 10 | Fuel type frequency analysis |
| 11 | Average premium by vehicle age category |
| 12 | Claims rate by vehicle age |
| 13 | Vehicle power categories and premium impact |
| 14 | Correlation heatmap across numerical variables |
| 15 | Key findings summary |

---

## 📊 Key Findings

- **Average premium** sits around **€316**, with most policies clustering between €200–250
- Only **~a small fraction** of policies filed a claim in the year — the portfolio is overwhelmingly claim-free
- **Higher-power vehicles** (101 hp+) attract meaningfully higher premiums
- **Vehicle age and value** are the strongest correlates with premium level
- **Petrol** is the dominant fuel type across the portfolio
- Claim rate shows a notable uptick in the **older vehicle (25+ years)** bracket

---

## 🛠️ Tech Stack

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

No external ML libraries required — pure EDA using the standard Python data stack.

---

## 📁 Repository Structure

```
├── Insurance_EDA_Template.ipynb   # Main analysis notebook
├── README.md                      # Project documentation
└── data/
    └── Motor_vehicle_insurance_data.csv   # Source dataset (not included — see below)
```

> **Dataset note:** The source CSV is not included in this repo due to file size. Download it from [Mendeley Data](https://data.mendeley.com) and place it in the `/data` folder before running the notebook.

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/<your-username>/motor-insurance-eda.git
cd motor-insurance-eda

# Install dependencies
pip install pandas matplotlib seaborn jupyter

# Launch notebook
jupyter notebook Insurance_EDA_Template.ipynb
```

> Update the file path in **Step 2** of the notebook to match where you saved the dataset locally.

---

## 📈 Next Steps

- Build a **claims probability model** (logistic regression / decision tree)
- Analyse **customer churn patterns** by policy tenure
- Deep-dive into **high-value policy** risk profiles
- Engineer features for a **premium prediction** regression model

---

## 👤 Author

**Lav Brar**  
Data Analyst | SQL · Python · Power BI · BigQuery  
[LinkedIn](https://www.linkedin.com/in/) · [GitHub](https://github.com/)

---

*Part of my data analytics portfolio. Feedback welcome — open an issue or connect on LinkedIn.*
