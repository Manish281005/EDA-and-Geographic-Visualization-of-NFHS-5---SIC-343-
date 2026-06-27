# 📊 EDA and Geographic Visualization of NFHS-5

## Overview

This project performs **Exploratory Data Analysis (EDA)** and **Geographic Visualization** on the **National Family Health Survey (NFHS-5)** dataset. The analysis focuses on state-wise health indicators such as obesity, anaemia, hypertension, and blood sugar levels using Python data science libraries.

---

# Output Screenshots

## 1. Dataset Preview

The dataset contains state-wise health statistics including obesity, anaemia, hypertension, and blood sugar percentages for both men and women.

![Dataset Preview](images/dataset_preview.png)

---

## 2. Feature Engineering

A new feature, **Gender Obesity Gap**, was created to measure the difference between male and female obesity percentages across Indian states.

**Formula**

```
Gender Obesity Gap = Women Obesity − Men Obesity
```

![Feature Engineering](images/gender_obesity_gap.png)

---

## 3. Correlation Matrix

The correlation matrix displays relationships among major health indicators.

Key observations:

- Women and Men obesity are strongly positively correlated.
- Children anaemia has a weak negative correlation with obesity.

![Correlation Matrix Table](images/correlation_table.png)

---

## 4. Correlation Heatmap

The heatmap visually represents correlations between obesity and anaemia indicators.

![Correlation Heatmap](images/correlation_heatmap.png)

---

## 5. Top 10 States by Hypertension

The following table lists the states with the highest hypertension percentages for men and women.

![Top 10 States Table](images/top10_states_table.png)

---

## 6. Hypertension Comparison

A grouped bar chart compares hypertension percentages between men and women across the top affected states.

![Hypertension Bar Chart](images/hypertension_bar_chart.png)

---

## 7. Anaemia vs Obesity Analysis

Scatter plot showing the relationship between women's anaemia and obesity percentages across Indian states.

Each point represents one state.

![Scatter Plot](images/anaemia_vs_obesity.png)

---

## 8. Geographic Visualization

Interactive India map displaying state-wise health indicators using color intensity and markers.

Example shown:

- High Blood Sugar (%)
- Anaemia (%)

Hovering over a state displays detailed statistics.

![Interactive Map](images/geographic_visualization.png)

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- GeoPandas
- Folium
- Jupyter Notebook / Google Colab

---

# Key Insights

- Significant variation exists in obesity rates across Indian states.
- Male and female obesity exhibit a strong positive correlation.
- Children's anaemia shows a slight negative relationship with obesity.
- Hypertension prevalence is higher among men in most states.
- Geographic visualization clearly highlights regional health disparities.

---

# Project Structure

```
EDA_and_Geographic_Visualization_of_NFHS_5/
│
├── README.md
├── requirements.txt
├── EDA_and_Geographic_Visualization_of_NFHS_5_SIC.ipynb
│
└── images/
    ├── dataset_preview.png
    ├── gender_obesity_gap.png
    ├── correlation_table.png
    ├── correlation_heatmap.png
    ├── top10_states_table.png
    ├── hypertension_bar_chart.png
    ├── anaemia_vs_obesity.png
    └── geographic_visualization.png
```

---

# Author

**Manish K**
