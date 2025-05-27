
# Exploratory data analysis on Titanic dataset

This project explores the Titanic dataset using Python libraries like **pandas**, **matplotlib**, and **seaborn**. It includes data cleaning, visualization, and insights into survival patterns.

## Dataset

The dataset used is `Titanic-Dataset.csv`, which includes passenger information such as class, fare, age, and survival status.

---

## Steps Performed

### 1. Data Cleaning

* Removed missing values with `dropna()`.
* Removed duplicate entries.

### 2. Summary Statistics

Used `df.describe()` to generate:

* Mean, median, standard deviation, and range of numerical columns.

### 3. Histograms

Plotted histograms for each numeric column (except PassengerId) to observe distributions.

### 4. Boxplots

* Visualized spread and outliers in numerical features.
* Horizontal layout for better readability.

### 5. Pairplot

Used seaborn's `pairplot()` to examine relationships and possible correlations between numeric features.

---

##  Observations & Insights

### Survival Trends

* Higher survival in 1st class, children, and women (if `Sex` is included).
* Lower survival in 3rd class, older males, and solo travelers.

### Age & Family

* Most passengers were aged 20–40.
* Moderate family sizes (SibSp/Parch = 1–3) showed higher survival.

### Fare & Class

* 1st class passengers paid the highest fares (some > \$200).
* 3rd class fares were mostly under \$20.

### Anomalies

* Some odd age entries (e.g., infants as fractions).
* A few zero fares (possibly crew members).

---

## Key Takeaway

Survival probability is strongly influenced by **class**, **age**, and **family size**. Visualizations help uncover trends and support feature engineering for machine learning.

---


