# Task 6: House Price Prediction

## Objective
The goal of this task is to predict house prices using features such as size, number of bedrooms, and location, helping buyers and sellers estimate property values accurately.

## Dataset
- **Dataset Name:** Housing Price Dataset
- **Source:** Kaggle (Housing.csv)
- **Features:**
  - Size (in square feet)
  - Number of bedrooms
  - Location
  - Other property-related features
- **Target Variable:** Price

## Steps Performed
1. **Data Loading:** Loaded dataset using pandas.  
2. **Data Inspection:**
   - Checked dataset shape and column names.
   - Displayed first few rows using `.head()`.
   - Checked for missing values using `.info()` and `.isnull().sum()`.
3. **Data Preprocessing:**
   - Dropped rows with missing target values (Price).  
   - Handled missing values in features (filled with median).  
   - Converted categorical features (like Location) to numeric using one-hot encoding.  
   - Replaced infinities with NaN.
4. **Data Splitting:** Split dataset into training (80%) and testing (20%) sets.  
5. **Model Training:** Applied Linear Regression to train the model.  
6. **Model Evaluation:** Calculated Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).  
7. **Visualization:**
   - Scatter plot of actual vs predicted prices.
   - Line plot comparison of actual and predicted prices.
8. **Libraries Used:** pandas, numpy, matplotlib, seaborn, scikit-learn

## Key Findings
- Linear Regression predicts house prices reasonably based on size, bedrooms, and location.  
- MAE and RMSE indicate average prediction error.  
- Location and square footage are the most influential features.  
- Visualization shows predicted prices closely follow actual prices.

## Conclusion
Regression modeling on housing data allows estimation of property prices with interpretable errors. The model can be improved using advanced regression algorithms or more features.
