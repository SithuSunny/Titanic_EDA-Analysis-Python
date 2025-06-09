# Titanic Dataset – Exploratory Data Analysis (EDA)

## Objective:
To extract meaningful patterns and insights from the Titanic dataset using statistical analysis and visualization.

## Tools Used:
- Python
- Jupyter Notebook
- Pandas, Matplotlib, Seaborn

##  Process Followed:

1. **Data Loading and Overview**
   - Used `.info()`, `.describe()`, `.value_counts()` to understand structure and missing values.

2. **Data Cleaning**
   - Filled missing Age with median, Embarked with mode.
   - Dropped 'Cabin' column due to too many nulls.

3. **Univariate Analysis**
   - Plotted Age and Fare distributions using histograms and boxplots.

4. **Bivariate/Multivariate Analysis**
   - Used `sns.pairplot`, `heatmap`, `scatterplot`, `countplot` to compare survival with:
     - Age
     - Fare
     - Gender
     - Passenger Class

5. **Observations**
   - Female passengers and 1st class had higher survival rates.
   - Fare was positively correlated with survival.
   - Age distribution was right-skewed.
   - Many 3rd class passengers did not survive.

## 📁 Files Included:
- Titanic_EDA.ipynb 
- Titanic_EDA.pdf 
- README.md

## ✅ Outcome:
Improved understanding of EDA process and storytelling with data. Built strong insights using visual tools.

