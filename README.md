# 🧠 Customer Personality Analysis

This project aims to perform an exploratory data analysis (EDA) and derive insights into customer behaviors using machine learning and data visualization techniques. The dataset contains information about a company's marketing campaign and customer attributes.

## 🧾 Dataset Description

The dataset includes the following features:

- **Customer Demographics**: Age, Education, Marital Status, Income
- **Purchasing Behavior**: Spending on different product categories (e.g., wines, fruits, meat)
- **Marketing Response**: Acceptance of campaigns, number of web visits, etc.

> Note: Ensure categorical columns are properly encoded or excluded for numerical operations like correlation analysis.

## 📊 Key Features

- **Correlation Heatmap**: Displays relationships between numeric features.
- **Distribution Plots**: Show how various customer traits are distributed.
- **Insights into Marketing Effectiveness**: Identifies the success rate of marketing campaigns.
- **Segmentation**: Understands customer segments by age, income, and other attributes.

## 🔧 Tools & Technologies

```python
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```

- **Python 3**
- **Pandas** for data manipulation
- **NumPy** for numerical computation
- **Matplotlib** and **Seaborn** for data visualization
- **Jupyter Notebook** for analysis

## 📌 Future Improvements

- Use machine learning models for customer segmentation
- Develop a dashboard using Plotly or Streamlit
- Automate the EDA pipeline
