# Diabetes Prediction Project

## Project Overview
This project focuses on predicting whether a person has diabetes based on diagnostic data from the Pima Indian Diabetes Dataset. The dataset contains 768 entries and 8 clinical features such as glucose level, blood pressure, BMI, and more.

## Dataset
- Source: Pima Indian Diabetes Dataset (CSV file)
- Features (columns): 
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
  - Outcome (target: 0 = No diabetes, 1 = Diabetes)

## Steps Performed
1. **Data Loading and Exploration**
   - Loaded the dataset using pandas.
   - Previewed the first few rows.
   - Checked data info, summary statistics, and missing/null values.
   - Identified columns with zero values where zeros are unlikely (e.g., Glucose, BMI).

2. **Data Visualization**
   - Plotted histograms to visualize the distribution of each feature.
   - Created a correlation heatmap to understand relationships between features.
   - Visualized the balance of the target variable (Outcome).

3. **Modeling**
   - Split the dataset into training and testing sets.
   - Trained a Logistic Regression model to predict diabetes.
   - Evaluated the model using accuracy score, confusion matrix, and classification report.

4. **Findings & Next Steps**
   - The model achieved a baseline accuracy (see console output).
   - There are some zero values in features where it doesn’t make sense medically, suggesting data cleaning or feature engineering is needed.
   - Next steps include trying other models like Random Forest or SVM, performing feature normalization, and handling zero-value imputation.

## How to Run
1. Make sure you have Python installed (recommended Python 3.7+).
2. Install dependencies using pip:

3. Update the path to the dataset in the script (`diabetes.csv`).
4. Run the Python script to perform analysis and modeling.

## Notes
- The orange line in distribution plots is the Kernel Density Estimate (KDE), which smooths the data distribution for better visualization.
- Zero values in some columns are placeholders for missing data and should be handled carefully.

---

Feel free to reach out if you have any questions or want to collaborate!

---

**Author:** Michael Lam  
**Date:** 2025-05-21
