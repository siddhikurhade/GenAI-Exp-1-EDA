# Experiment No. 1: Exploratory Data Analysis (EDA) and Data Preprocessing Using Python

## Aim
To analyze, clean, visualize, and prepare datasets using Python libraries for Data Science and Machine Learning.

## Objectives
1. Understand the concepts of EDA and data preprocessing.
2. Load and summarize datasets using Pandas and NumPy.
3. Handle missing values and duplicate records.
4. Calculate descriptive statistics.
5. Detect outliers using IQR, Z-scores, and boxplots.
6. Perform feature scaling and categorical encoding.
7. Visualize data and analyze correlations.
8. Perform grouping and aggregation.

## Pre-Requisites
- Basic Python programming.
- Basic statistics and mathematical knowledge.
- Familiarity with datasets and Jupyter Notebook or Google Colab.
- Basic knowledge of Python package installation using `pip`.

## Theory
**Exploratory Data Analysis (EDA)** helps understand a dataset by examining its structure, patterns, relationships, and unusual values.

**Data Preprocessing** prepares raw data for analysis by handling missing values, duplicates, outliers, and inconsistent formats.

Main techniques include:

- **Descriptive Statistics:** Mean, median, mode, variance, and standard deviation summarize data.
- **Missing Values:** Identified using `isnull()` and handled through imputation or removal.
- **Duplicates:** Identified using `duplicated()` and removed using `drop_duplicates()`.
- **Data Visualization:** Histograms, bar plots, scatter plots, boxplots, and heatmaps reveal patterns.
- **Correlation Analysis:** Measures relationships between numerical variables.
- **Outlier Detection:** Uses boxplots, IQR, and Z-scores to identify unusual observations.
- **Feature Scaling:** `StandardScaler`, `MinMaxScaler`, `RobustScaler`, and `Normalizer` transform numerical features.
- **Categorical Encoding:** Label encoding and one-hot encoding convert categories into numerical representations.
- **Grouping and Aggregation:** `groupby()` summarizes data by categories.

Datasets used include Titanic, Iris, Tips, Penguins, and California Housing.

## Procedure
1. Import the required Python libraries.
2. Load and inspect datasets using Pandas.
3. Calculate descriptive statistics.
4. Identify and handle missing values and duplicates.
5. Visualize data distributions and relationships.
6. Detect potential outliers using IQR and Z-scores.
7. Apply feature scaling and categorical encoding.
8. Perform correlation analysis and grouping.
9. Clean the Titanic dataset and save it as `titanic_cleaned.csv`.
10. Observe and interpret the results.

## Conclusion
This experiment demonstrates EDA and data preprocessing using Python. It provides practical knowledge of data cleaning, statistical analysis, visualization, outlier detection, scaling, encoding, and aggregation, forming a foundation for Data Science and Machine Learning.

