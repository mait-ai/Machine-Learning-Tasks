#  CampusPulse — Student Life Analytics & Prediction

##  Task Summary
CampusPulse is a data science project designed to analyze student life patterns using anonymized survey data. The objective is to uncover meaningful insights and build a model to predict if a student is likely to be in a romantic relationship.

## Notebook Overview

###  Task 1 — Levels Breakdown

#### Level 1: Variable Identification Protocol
- Loaded the dataset and began exploratory analysis.
- Used correlation heatmaps and scatterplots to deduce what `Feature_1`, `Feature_2`, and `Feature_3` might represent.
- Suggested possible identities (e.g., GPA, screen time, etc.) based on statistical behavior.

#### Level 2: Data Integrity Audit
- Detected null values and inconsistencies.
- Imputed values using mean, mode, and conditional strategies.
- Clearly justified every imputation approach with markdown explanations.

#### Level 3: Exploratory Insight Report
- Explored questions such as:
  - Q1: Does parental education affects student's academic performance?
  - Q2: Does weekday alcohol consumptions affects the academic performanace?
  - Q3: How does free time influence going out?
  - Q4: Does living lifestyle affects student's academic performance?
  - Q5: Does travel time reduce a student’s free time?
- Included visualizations: bar plots, box plots, violin plots, etc.
- Each visualization is followed by a short but sharp insight.

#### Level 4: Relationship Prediction Model
- Applied multiple classifiers (Logistic Regression, Random Forest, XGBoost).
- Evaluated using accuracy, F1-score, ROC curves.
- Discussed strengths and weaknesses of each model.

#### Level 5: Model Reasoning & Interpretation
- Used SHAP for global and local interpretability.
- Visualized decision boundaries with selected feature pairs.
- Explained decisions for both "Yes" and "No" predictions in plain language.

## Files Included
- `CampusPulseTask.ipynb`: Jupyter notebook with code and explanations.
- `CampusPulse_Report.pdf`: Complete write-up of approach, analysis, results.

## Tools & Libraries
- Python, Pandas, Seaborn, Matplotlib, Scikit-learn, SHAP

## Notes
- All plots are labeled and interpreted.
- Markdown sections clearly guide the reader through the logic and learning process.
