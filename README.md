# New-Coder-Survey-Data-Analysis-Machine-Learning
This project analyses the 2021 New Coder Survey dataset to explore demographic, educational, and income patterns among new programmers.

## Features
- **Data Cleaning & Preprocessing**
  - Handles missing values and inconsistent responses
  - Feature engineering (income categorization, gender normalization, etc.)
  - Outlier removal for age and other metrics
- **Exploratory Data Analysis (EDA)**
  - Visualisations with Seaborn & Matplotlib (income distribution, gender ratios, education levels, regional representation)
  - Statistical summaries and boxplots for demographic insights
- **Clustering & Pattern Detection**
  - K-Means clustering on various feature combinations (region, income level, age, weekly coding hours)
  - Elbow method to determine optimal cluster count
- **Classification Models**
  - Decision Tree Classifier (predicting high vs. low income)
  - Model evaluation using accuracy, precision, recall, F1-score, and confusion matrices
  - Logistic Regression for comparison

## Tools & Libraries
pandas, numpy, matplotlib, seaborn, scikit-learn, geopandas

## Use Case
Provides insights into socio-economic and learning trends among new coders, while demonstrating clustering and classification techniques on a real-world dataset.
