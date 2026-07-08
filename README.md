# California Housing Price Prediction

A linear regression model trained to predict median house prices across California districts using 8 features including location, house age, and income.

---

## 📊 Dataset
* **California Housing Dataset** (built into `scikit-learn`)
* **Size:** 20,640 districts

---

## 🔑 Key Findings
* **Median income** was the strongest predictor of house price (correlation of **0.69**). This is consistent with real-world intuition that wealthier areas tend to have higher property values.

---

## 🛠️ Tools Used
* Python
* Pandas
* scikit-learn
* Matplotlib
* Seaborn

---

## ⚠️ Limitations and Next Steps
* **Data Capping:** House prices are capped at $500,000 in this dataset, which distorts predictions for high-value areas.
* **Model Improvement:** A tree-based model (like Random Forest or XGBoost) could likely capture non-linear patterns better than linear regression.

---

## 📁 Files Included
* `task1_ml_linear_regression.ipynb` — Full notebook with code, EDA, and analysis.
* `Task-1 report.pdf` — Exported report with results and findings.
