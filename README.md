# 🍽️ Predicting Restaurant Tips — Multiple Regression Analysis

## 📌 Project Overview
This project analyses a restaurant tips dataset to identify factors 
that influence tipping behaviour and builds a multiple regression 
model to predict tip amounts.

## 📂 Files Included
| File | Description |
|------|-------------|
| `Restaurant_tips_dataset.xlsx` | Original raw dataset |
| `restaurant_tips_analysis.xlsx` | Full Excel analysis with pivot tables, charts, correlation, and regression |
| `restaurant_tips_report.docx` | Detailed written report of findings |

## 🔧 Tools Used
- Microsoft Excel (Data Analysis ToolPak)
- Multiple Linear Regression (OLS)

## 📊 Key Findings
- **Total bill** is the strongest predictor of tip (r = 0.68)
- **Table size** is the second most influential factor (r = 0.49)
- Gender, smoking status, day and time have negligible impact
- Regression R² = 0.47 (model explains 47% of tip variation)

## 🧮 Regression Equation
Tip = 0.6689 + 0.0927×total_bill + 0.1759×size + 0.0324×sex 
      + 0.0801×smoker − 0.0134×day + 0.0069×time
