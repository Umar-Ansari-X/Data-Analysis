# Data-Analysis
Practice on analyzing databases, inferential and descriptive analysis

---

## How It’s Made

**Tech used:** Python, Jupyter Notebook, pandas, NumPy, Matplotlib, Seaborn, SciPy, scikit-learn

* **Data ingest & cleaning** – reads `project_dataset.csv`, converts “?” to `NaN`, drops mostly empty columns (`weight`, `max_glu_serum`)
* **Descriptive EDA** – dimensionality check , missing-value audit, and per-column summary
* **Visuals** – histograms, bar charts, heat-map correlation matrix and more
* **Inferential tests** –  t-tests on *time-in-hospital* groups, ANOVA for race differences and more 
* **Baseline model** – logistic regression that predicts 30-day readmission


---

## Getting Started

```bash
# 1 – Clone
git clone https://github.com/Umar-Ansari-X/Data-Analysis.git
cd Data-Analysis

# 2 – Launch notebook
jupyter notebook dataanalyzed.ipynb
