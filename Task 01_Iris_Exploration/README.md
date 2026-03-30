# Task 1: Iris Dataset Exploration

## Objective
The goal of this task is to explore and visualize the Iris dataset to understand trends, relationships, and distributions of features.

## Dataset
- **Dataset Name:** Iris Dataset("iris.csv")
- **Source:** Available in CSV format
- **Features:**
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width
- **Target:**
  - Species

## Steps Performed
1. **Data Loading:** Loaded the dataset using pandas.
2. **Data Inspection:**
   - Checked shape and column names.
   - Displayed first few rows using `.head()`.
   - Used `.info()` and `.describe()` for summary statistics.
3. **Data Visualization:**
   - Scatter plots to show relationships between features.
   - Histograms to see value distributions.
   - Box plots to identify outliers.
4. **Libraries Used:** pandas, matplotlib, seaborn

## Key Findings
- No missing values in the dataset.
- Petal length and petal width are strongly correlated.
- Sepal length and width show moderate correlation.
- Box plots indicate a few outliers in sepal width and petal width.
- Visualization helps understand feature distributions for further analysis or modeling.

## Conclusion
Exploratory Data Analysis (EDA) helps to understand dataset structure and feature relationships before applying any machine learning models. The Iris dataset is clean, with distinct patterns across different species.
