# 🍬 Diabetes Patient Data Analysis

This project analyzes clinical data from the Pima Indian Diabetes dataset to uncover patterns and build a predictive model for diabetes diagnosis. The goal is to explore important health factors and demonstrate how data analysis can support early disease detection.

## 📊 Project Overview

Using a well-known diabetes dataset, this notebook performs exploratory data analysis, data visualization, and applies a basic logistic regression model to classify patients as diabetic or non-diabetic based on medical measurements. The project walks through the steps from data cleaning to model evaluation.

## 📁 Dataset

- **Source**: [Pima Indian Diabetes Database - Kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database)  
- **File Used**: `diabetes.csv`  
- **Columns**:  
  - `Pregnancies`  
  - `Glucose`  
  - `BloodPressure`  
  - `SkinThickness`  
  - `Insulin`  
  - `BMI`  
  - `DiabetesPedigreeFunction`  
  - `Age`  
  - `Outcome` (0 = No Diabetes, 1 = Diabetes)

## 📌 Objectives

- Explore patient data for diabetes risk factors  
- Visualize feature distributions and relationships  
- Identify data quality issues such as zero or missing values  
- Build and evaluate a logistic regression model for diabetes prediction  
- Understand key clinical indicators associated with diabetes  

## 🧠 Key Insights

- Certain features like Glucose, BMI, and Age show clear differences between diabetic and non-diabetic patients.  
- Zero values in features like BloodPressure and Insulin likely indicate missing data and affect analysis quality.  
- Visualizations reveal skewed data distributions and correlations that inform model building.  
- The logistic regression model achieves reasonable accuracy, highlighting its usefulness for early screening.

## 📈 Visualizations

- **Histograms + KDE**: Show the distribution and density of clinical features.  
- **Correlation Heatmap**: Highlights relationships between variables, especially between glucose and insulin.  
- **Outcome Distribution**: Visualizes class balance between diabetic and non-diabetic patients.  
- **Confusion Matrix**: Evaluates model classification performance visually.

## 🏥 Real-World Healthcare Applications

- Early identification of patients at risk for diabetes through clinical data analysis  
- Informing healthcare providers about key risk factors to monitor  
- Supporting data-driven personalized care and preventive health strategies  
- Enhancing clinical decision support systems with predictive modeling  

## 📌 Conclusion

This project demonstrated how clinical features can be explored and modeled to predict diabetes diagnosis. Further work can improve data cleaning, test other models, and incorporate additional patient information for more accurate predictions.

## 📂 File List

- `Michael Lam Diabetes Dataset.ipynb`: Main Jupyter Notebook with analysis and modeling  
- `diabetes.csv`: Original dataset file  

---

## 🚀 Author

Michael Lam  
📍 Application Analyst | Healthcare IT | Data Analytics  
https://github.com/Michaellam001

---

## 📄 License

This project is for educational purposes. Dataset provided by Kaggle and UCI Machine Learning Repository.
