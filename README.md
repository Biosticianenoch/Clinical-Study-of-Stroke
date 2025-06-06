
# 🧠 Clinical Study of Stroke  
### _Data Analysis & Predictive Modeling in R_  
**By Wakasala Nobert & Enock Bereka**  
📅 **Completed: February 7, 2025**

---

## 📌 Overview

This project presents an extensive **clinical data analysis of stroke** using R. Our goal was to explore, visualize, and model the **factors contributing to stroke**, leveraging statistical methods and machine learning tools to derive meaningful health insights. The dataset comprises 5,110 patient records and 12 clinical and lifestyle-related variables.

---

## 🎯 Study Objectives

- 🔍 Explore the **demographic, lifestyle, and medical** variables linked with stroke occurrence.
- 📊 Apply **univariate, bivariate**, and **multivariate statistical techniques** to examine relationships and trends.
- 📈 Build a robust **logistic regression model** to predict the likelihood of stroke based on risk factors.
- 🧪 Evaluate statistical significance, model assumptions, feature importance, and prediction accuracy.

---

## 🧪 Key Tools and Libraries

- **Data Manipulation & Visualization:** `tidyverse`, `ggplot2`, `ggcorrplot`, `sjPlot`, `vip`
- **Statistical Modeling:** `glm`, `chisq.test`, `t.test`, `car`, `pROC`
- **Reporting & Summary:** `gtsummary`, `report`, `ggeffects`, `performance`

---

## 🔍 Key Findings

- 👵 **Age** was the **strongest predictor** of stroke: Risk increases significantly with age (_OR = 1.08_ per year, _p < 0.001_).
- 💉 **Hypertension** had a **significant positive association** with stroke (_p < 0.001_).
- ❤️ **Heart disease** was statistically linked to higher stroke prevalence (_p < 0.001_).
- 🚬 **Smoking status** and **marital status** also showed significant associations.
- 💊 Higher **BMI** and **average glucose levels** correlated with increased stroke risk.
- 🧠 The **logistic regression model** had an impressive **AUC of 0.853**, making it a highly effective classifier.

---

## 📈 Visual Highlights

- Age, glucose, and BMI distributions with histograms and density plots.
- Bar plots showing categorical distributions by stroke outcome.
- Chi-square tests visualized through grouped bar charts.
- Model performance visualized with ROC curve and VIP (Variable Importance Plot).

---

## 🤖 Model Summary

| Metric                  | Value          |
|------------------------|----------------|
| **Model Type**         | Logistic Regression |
| **Key Predictors**     | Age, BMI, Avg Glucose |
| **AUC (ROC)**          | 0.853 |
| **Significant Factors**| Age (p<0.001), BMI (p<0.001), Glucose (p<0.01) |

---

## ✅ Recommendations

- 💡 **Early screening programs** should target **older, hypertensive, and obese individuals**.
- 🏥 **Public health interventions** should address **lifestyle factors** (smoking, BMI, glucose control).
- 🧬 Incorporate **clinical decision support systems** using predictive models like this to aid diagnosis.
- 📚 Further research could explore **non-linear models**, **ensemble methods**, or **deep learning** to improve predictive performance.

---

## 📂 Folder Structure (Suggested for GitHub)

```
/clinical-study-stroke
│
├── data/                  # Raw and cleaned dataset
├── scripts/               # R scripts for analysis
├── plots/                 # Generated visualizations
├── report/                # PDF or HTML report
├── README.md              # This README
└── stroke_analysis.Rproj  # R Project file
```

---

## 🙌 Acknowledgments

Thanks to the open-source R community and the contributors of the stroke dataset used in this analysis. This project was developed as part of our ongoing commitment to **data-driven healthcare solutions** at **DataQuest Solutions**.

---

## 🔗 Connect With Me

📧 Email: nobertwakasala@gmail.com  
💼 LinkedIn: [Wakasala Nobert](https://www.linkedin.com/in/your-profile)  
🌐 Website: [Coming soon on Vercel 🚀]
