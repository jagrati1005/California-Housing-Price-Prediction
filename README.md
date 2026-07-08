A linear regression model trained to predict median house prices across California district, which uses 8 features including location, house age and income.

Dataset
California Housing Dataset (built into scikit-learn), 20,640 districts.

Key Findings
Median income was the strongest predictor of house price (correlation of 0.69) — consistent with real-world intuition that wealthier areas tend to have higher property values.

Tools Used
Python, Pandas, scikit-learn, Matplotlib, Seaborn

Limitations and Next Step
House prices are capped at $500,000 in this dataset, which distorts predictions for high-value areas
A tree-based model could likely capture non-linear patterns better than linear regression.

Files
task1_ml_linear_regression.ipynb — full notebook with code, EDA, and analysis
Report_Task1.pdf — exported report with results and findings
