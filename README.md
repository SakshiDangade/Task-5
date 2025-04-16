# 🧠 Task 5: Exploratory Data Analysis (EDA) - Titanic Dataset

## 📌 Objective:
Perform Exploratory Data Analysis to uncover patterns, trends, and relationships in the Titanic dataset using Python and visualization libraries.

---

## 🛠 Tools & Libraries Used:
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab (instead of Jupyter Notebook)

---


## 📊 Key Steps Performed:

1. **Data Loading & Exploration**
   - Loaded `train.csv`, `test.csv`, and `gender_submission.csv`
   - Explored structure with `.info()`, `.describe()`, `.isnull().sum()`, and `.value_counts()`

2. **Data Cleaning**
   - Filled missing `Age` values with median
   - Dropped `Cabin` due to excessive missing values
   - Ensured no missing data remains

3. **Univariate Analysis**
   - Countplots for `Survived`, `Sex`, `Pclass`
   - Histograms for `Age` and `Fare`

4. **Bivariate Analysis**
   - Bar plots: `Sex` vs `Survived`, `Pclass` vs `Survived`
   - Boxplot: `Survived` vs `Age`
   - FacetGrid of `Age` by `Survived`

5. **Multivariate Analysis**
   - Pairplot of `Survived`, `Age`, `Fare`, `Pclass`
   - Heatmap of correlation between numeric features

6. **Analysis of `gender_submission.csv`**
   - Explored what the gender-based prediction file contains
   - Clarified that it assumes all females survived and all males didn’t

---

## 🧠 Key Insights:
- Females had much higher survival rates than males.
- First-class passengers had better survival outcomes.
- Younger passengers had slightly better survival chances.
- Most passengers paid low fares; very few paid extremely high fares.
- The `gender_submission.csv` is a simple prediction file used as a baseline.

---

## ✅ Outcome:
- Learned to perform EDA using Python.
- Gained insights using visual and statistical methods.
- Understood patterns in the Titanic dataset.
- Delivered both code and an interpretable PDF report.

