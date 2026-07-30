# Heart Health Analysis

## Project Overview

The **Heart Health Analysis** project focuses on analyzing patient health records to identify patterns, risk factors, and clinical indicators associated with heart disease. The project combines **Exploratory Data Analysis (EDA)** and **Machine Learning** to uncover meaningful insights from healthcare data and build a predictive model for heart disease classification.

The project was developed using **Python**, **Pandas**, **NumPy**, **Matplotlib**, and **Scikit-learn**, following a complete data analysis workflow that includes data cleaning, preprocessing, exploratory data analysis, feature scaling, model building, and evaluation.

---

# Project Highlights

- Performed comprehensive Exploratory Data Analysis (EDA) on patient health records.
- Conducted data cleaning and preprocessing.
- Detected and analyzed outliers in numerical features.
- Applied feature scaling using MinMaxScaler.
- Created multiple visualizations to understand relationships between health indicators.
- Built a Logistic Regression model to predict heart disease.
- Evaluated the model using a Confusion Matrix.
- Generated business and healthcare insights from the analysis.

---

# Problem Statement

Heart disease is one of the leading causes of death worldwide. Early identification of individuals at risk can significantly improve treatment outcomes and reduce mortality.

The objectives of this project are to:

- Analyze patient health characteristics.
- Identify important risk factors associated with heart disease.
- Study relationships between clinical variables.
- Explore trends through data visualization.
- Build a machine learning model to predict heart disease.
- Support data-driven healthcare decision-making.

---

# Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- MinMaxScaler
- Logistic Regression
- Confusion Matrix
- Exploratory Data Analysis (EDA)

---

# Dataset Source

**Dataset Name:** Heart Disease Dataset

**Dataset Source:** Kaggle / UCI Machine Learning Repository

---

# Dataset Description

The dataset contains clinical information collected from patients to determine the presence or absence of heart disease.

| Column | Description |
|---------|-------------|
| age | Age of the patient |
| sex | Gender (1 = Male, 0 = Female) |
| cp | Chest pain type |
| trestbps | Resting blood pressure |
| chol | Serum cholesterol level |
| fbs | Fasting blood sugar |
| restecg | Resting electrocardiographic results |
| thalach | Maximum heart rate achieved |
| exang | Exercise-induced angina |
| oldpeak | ST depression induced by exercise |
| slope | Slope of the peak exercise ST segment |
| ca | Number of major vessels colored by fluoroscopy |
| thal | Thalassemia type |
| target | Heart disease status (0 = No Disease, 1 = Disease) |

---

# Data Analysis Workflow

## Data Loading

- Imported the Heart Disease dataset.
- Loaded data into Pandas DataFrame.

## Data Understanding

Performed initial exploration using:

- Dataset Shape
- Dataset Information
- Statistical Summary
- Missing Value Analysis
- Duplicate Record Analysis
- Unique Value Inspection
- Data Type Verification

## Data Cleaning

Performed the following preprocessing steps:

- Removed duplicate records.
- Verified data quality.
- Checked missing values.
- Prepared the dataset for analysis.

## Outlier Detection

Analyzed numerical columns for potential outliers using visualizations and statistical methods.

## Feature Scaling

Applied **MinMaxScaler** to normalize numerical features before training the machine learning model.

---

# Exploratory Data Analysis

The following analyses were performed:

- Age Distribution
- Gender Distribution
- Chest Pain Type Analysis
- Blood Pressure Analysis
- Cholesterol Distribution
- Fasting Blood Sugar Analysis
- ECG Result Analysis
- Maximum Heart Rate Analysis
- Exercise-Induced Angina Analysis
- Oldpeak Analysis
- Major Vessels Analysis
- Thalassemia Analysis
- Age vs Cholesterol
- Chest Pain by Age
- Cholesterol Comparison by Heart Disease
- Blood Pressure Comparison
- Correlation Heatmap
- Pairplot of Risk Factors

---

# Machine Learning

A predictive model was developed to classify patients based on the likelihood of heart disease.

### Algorithm Used

- Logistic Regression

### Model Evaluation

- Confusion Matrix

The model demonstrates how machine learning can assist healthcare professionals in predicting heart disease using patient clinical data.

---

# Key Visualizations

The project includes visualizations such as:

- Correlation Heatmap
- Age vs Cholesterol
- Chest Pain Distribution
- Chest Pain by Age
- Cholesterol Comparison by Heart Disease
- Exercise-Induced Angina Analysis
- Average Oldpeak by Chest Pain Type
- Fasting Blood Sugar Distribution
- Combined Risk Factors Pairplot
- Confusion Matrix

---

# Key Business Insights

- Older patients generally show a higher risk of heart disease.
- Certain chest pain types are more strongly associated with heart disease.
- Patients with exercise-induced angina have a greater likelihood of heart disease.
- Higher cholesterol and blood pressure contribute to increased cardiovascular risk.
- Maximum heart rate varies significantly between patients with and without heart disease.
- Multiple clinical factors together improve disease prediction.
- Correlation analysis helps identify important relationships among medical variables.

---

# Challenges Faced

During the development of this project, several challenges were encountered:

- Understanding medical terminology and clinical variables.
- Identifying meaningful relationships between multiple health indicators.
- Detecting and handling outliers.
- Scaling numerical features for machine learning.
- Selecting appropriate visualizations for healthcare analysis.
- Building an interpretable prediction model.

---

# Recommendations

Based on the analysis, the following recommendations are suggested:

- Encourage regular health checkups for high-risk individuals.
- Monitor cholesterol and blood pressure levels consistently.
- Promote healthy lifestyle habits including exercise and balanced nutrition.
- Use predictive analytics to assist early diagnosis.
- Focus preventive healthcare programs on patients with multiple risk factors.
- Continue collecting patient data to improve predictive model performance.

---

# Output Images

The project generates multiple visualizations, including:

- Correlation Heatmap
- Age vs Cholesterol
- Chest Pain Distribution
- Chest Pain by Age
- Cholesterol Comparison by Heart Disease
- Exercise-Induced Angina
- Average Oldpeak by Chest Pain Type
- Fasting Blood Sugar Distribution
- Combined Risk Factors Pairplot
- Confusion Matrix

---

# Project Structure

```
Heart-Health-Analysis/
│
├── Dataset/
│   └── heart.csv
│
├── Output Images/
│   ├── age_vs_cholesterol.png
│   ├── chest_pain_distribution_by_age.png
│   ├── chest_pain_type_distribution.png
│   ├── cholesterol_comparison_by_heart_disease.png
│   ├── combined_risk_factors_pairplot.png
│   ├── confusion_matrix.png
│   ├── correlation_heatmap.png
│   ├── exercise_induced_angina.png
│   ├── fasting_blood_sugar_distribution.png
│   ├── average_oldpeak_by_chest_pain.png
│   └── ...
│
├── Heart Health Analysis.ipynb
│
└── README.md
```

---

# Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Data Preprocessing
- Outlier Detection
- Feature Scaling
- Statistical Analysis
- Data Visualization
- Correlation Analysis
- Machine Learning
- Logistic Regression
- Model Evaluation
- Healthcare Data Analytics
- Python Programming
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

# Project Outcome

This project demonstrates a complete healthcare data analytics workflow by transforming raw patient records into meaningful clinical insights and predictive analytics. The combination of Exploratory Data Analysis and Machine Learning helps identify important cardiovascular risk factors and supports early detection of heart disease using data-driven techniques.

---

# Future Enhancements

- Evaluate additional machine learning models such as Decision Tree, Random Forest, and XGBoost.
- Compare multiple classification algorithms.
- Calculate additional evaluation metrics such as Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
- Develop an interactive healthcare dashboard using Power BI or Tableau.
- Integrate real-time patient health monitoring data.
- Deploy the prediction model as a web application.

