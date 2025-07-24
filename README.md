
# 📊 Finance Data EDA Project

This project performs **Exploratory Data Analysis (EDA)** on a finance dataset containing survey responses on investment preferences, reasons for investing, and demographic details like age and gender.

---

## 📁 Dataset Overview

- **Source:** Kaggle (Uploaded CSV)
- **File Used:** `Finance_data.csv`
- **Rows:** 40
- **Columns:** 24
- **Content:** Survey responses on preferred investment instruments, reasons, savings objectives, and demographic info

---

## 📌 Goals of the Project

- Understand investment behavior across age and gender
- Visualize reasons for investment in different instruments
- Identify most and least preferred investment avenues
- Analyze expected return patterns and savings goals

---

## 🔍 Key EDA Steps

### ✅ 1. Data Loading and Preview
- Used `pandas` to load and inspect the dataset.
- Checked structure, types, and basic statistics.

### ✅ 2. Bar Charts of Categorical Variables
- Visualized counts of:
  - Savings objectives
  - Reasons for choosing Equity, Mutual Funds, Bonds, and FDs
  - Preferred investment avenues

### ✅ 3. Age Distribution by Gender
- Used `sns.swarmplot` to show how age is distributed across male and female respondents.

### ✅ 4. Government Bonds Preference by Gender
- Used `sns.barplot` to show average rank (preference) for Government Bonds by gender.

### ✅ 5. Statistical Summary
- Used `df.describe()` to analyze distributions and central tendencies for numeric fields like `age`, `Mutual_Funds`, etc.

### ✅ 6. Investment Preference vs Age
- Visualized with a regression plot (`sns.lmplot`) to identify age-related trends in mutual fund preferences.

### ✅ 7. Gender-Based Average Preferences
- Bar charts showing average ranks given to each investment avenue by Male and Female respondents.

---

## 📈 Key Insights Extracted

- **Mutual Funds** are the most preferred investment overall.
- **Better Returns** and **Fixed Returns** are common reasons for investment.
- **Males and females** differ slightly in their preferences for Government Bonds.
- Most participants expect **20–30% returns**, indicating a high-return mindset.
- Age has a **mild trend** with respect to preference for Mutual Funds.

---

## 🛠 Tools Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📂 File Structure

```
.
├── Finance_data.csv
├── Finance_Data_Analysis.ipynb
├── README.md
└── eda_finance_summary.md
```

---

## 🙋‍♀️ Author

This project was created as a part of hands-on learning to explore EDA and build data storytelling skills using Python.

Feel free to fork, clone, or contribute!
