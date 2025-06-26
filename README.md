# 🚢 Titanic Survival Analysis – Exploratory Data Analysis (EDA)

This project explores the Titanic dataset to identify patterns that influenced passenger survival using data visualization and statistical analysis in Python.

---

## 📌 Objective
Perform a structured exploratory data analysis (EDA) to uncover trends in survival based on gender, passenger class, age, and fare.

---

## 🧰 Tools & Technologies
- **Language:** Python
- **Libraries:** Pandas, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

---

## 📂 Dataset
- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)
- **Records:** 891 passengers
- **Features:** Age, Sex, Pclass, Fare, SibSp, Parch, Embarked, etc.

---

## 🔍 Analysis Workflow

### 1. Data Loading and Initial Exploration
- Imported dataset using Pandas
- Used `.info()`, `.describe()`, and `.value_counts()` to understand structure

### 2. Data Cleaning
- Handled missing values in `Age` and `Embarked`
- Dropped `Cabin` due to high null count

### 3. Univariate Analysis
- Age: Most passengers were 20–40 years old
- Fare: Right-skewed distribution with outliers

### 4. Bivariate & Multivariate Analysis
- Higher survival among females and 1st class passengers
- Visualized `Survived` vs `Sex`, `Pclass`, `Age`, and `Fare`

### 5. Correlation Analysis
- Heatmap showed:
  - Positive correlation: `Fare` (0.26)
  - Negative correlation: `Pclass` (-0.34)

---

## 📊 Key Insights

- 🎯 **Female passengers had higher survival rates than males.**
- 🛏️ **1st class passengers were more likely to survive.**
- 💸 **Fare is positively correlated with survival.**
- 🧒 **Most passengers were aged 20–40.**
- 🚪 **Majority of 3rd class passengers did not survive.**

---

## ✅ Outcome

This project demonstrates a structured approach to EDA, combining data cleaning, visualization, and insights communication. It showcases my data analysis skills using Python tools and storytelling through data.

---

## 📁 Files Included

- `Titanic_EDA_Final.ipynb` – Final analysis notebook
- `Titanic_EDA_Report.pdf` – Exported PDF version of the notebook
- `README.md` – Project overview and insights
