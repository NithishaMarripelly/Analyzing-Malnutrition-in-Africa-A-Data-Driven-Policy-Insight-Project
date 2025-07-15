# 🌍 Tackling Malnutrition in Africa – A Data-Driven Policy Insight Project

This project explores the key socio-economic and health-related factors influencing malnutrition in African countries. Using data from the World Bank and Python-based statistical analysis, we validated four hypotheses through correlation analysis and data visualization to uncover actionable insights for policymakers.

---

## 🧠 Objective

To investigate how variables like GDP, food affordability, maternal education, and immunization rates affect malnutrition levels across African countries and to provide data-backed insights for improving public health and policy planning.

---

## 📊 Dataset

- **Source**: [World Bank Open Data](https://databank.worldbank.org/source/world-development-indicators)
- **Format**: `.csv` files from the World Development Indicators & Africa Development Indicators
- **Variables Studied**:
  - Malnutrition Index (avg. of stunting, wasting, underweight)
  - GDP per capita
  - Cost of healthy diet per capita
  - Immunization coverage (BCG, DPT, Polio, Measles)
  - Female education (25+ years, upper secondary attainment)

---

## 📌 Hypotheses Tested

1. **Negative correlation** between GDP per capita and population unable to afford a healthy diet
2. **Positive correlation** between food prices and malnutrition
3. **Negative correlation** between immunization rates and malnutrition
4. **Negative correlation** between maternal education and malnutrition

---

## 📈 Tools & Technologies

- **Language**: Python
- **Libraries**: `Pandas`, `Matplotlib`, `NumPy`, `SciPy`
- **Methods Used**:
  - Pearson Correlation Coefficient
  - Spearman Correlation Coefficient
  - p-value testing for statistical significance
  - Scatter plots for visual analysis

---

## 📉 Results Summary

| Relationship | Pearson | Spearman | p-value | Conclusion |
|--------------|---------|----------|---------|------------|
| GDP vs Food Affordability | -0.79 | -0.74 | 4.5e-9 | Strong negative correlation |
| Food Price vs Malnutrition | 0.75 | 0.73 | 1.2e-7 | Strong positive correlation |
| Immunization vs Malnutrition | -0.65 | -0.59 | 1e-5 | Significant negative correlation |
| Maternal Education vs Malnutrition | -0.44 | -0.59 | 0.0014 | Moderate negative correlation |

> All hypotheses were supported by statistically significant results.

---

## 🧪 Project Highlights

- Cleaned and prepared real-world global health data using **Pandas**
- Applied **statistical testing** to validate relationships between variables
- Used **Matplotlib** for clear, interpretable scatter plots
- Offered **policy-level recommendations** based on findings


