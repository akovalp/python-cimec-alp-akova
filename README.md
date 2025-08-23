# Campus Placement Analysis

This project was completed for the 2025 CIMEC PhD Python course.

The primary goal of this notebook is to provide a straightforward demonstration of a complete data analysis workflow. This includes downloading data, performing exploratory data analysis  with visualizations, building predictive models, and reporting the findings.

---

## Dataset

The dataset used contains placement data for 215 students from a campus, including academic performance in secondary school, higher secondary school, and their undergraduate degree. It also includes details on work experience and salary offers.

The dataset can be downloaded from Kaggle: [Factors Affecting Campus Placement](https://www.kaggle.com/datasets/benroshan/factors-affecting-campus-placement)

---

## Project Workflow

1.  **Data Loading and Preprocessing:** The dataset was loaded using Pandas and column names were standardized for clarity.
2.  **Exploratory Data Analysis (EDA):** A thorough EDA was conducted to understand the data's structure, visualize feature distributions using count plots and box plots, and analyze relationships with a correlation heatmap.
3.  **Classification Modeling:** Built classification models (Logistic Regression, Random Forest, XGBoost) to predict student placement status.
4.  **Regression Modeling:** Built regression models (Linear Regression, Random Forest, XGBoost) to predict the salary of placed students.

---

## Key Findings & Conclusion

The analysis yielded two distinct outcomes for the prediction tasks:

* **Placement Status Prediction (Successful):** The classification models performed well, with Logistic Regression achieving the highest accuracy of **88%**. This indicates a clear, predictable relationship between a student's profile and their placement outcome.

* **Salary Prediction (Unsuccessful):** In contrast, all regression models built to predict salary performed poorly, yielding **negative R-squared ($R^2$) values**. This suggests that the salary data in this dataset is likely not realistic or has no discernible correlation with the provided features.

The complete analysis can be found in the `analysis.ipynb` notebook.