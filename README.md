# 🛳️ Titanic Dataset – Exploratory Data Analysis (EDA)

This project explores the Titanic dataset using Python to understand data patterns, handle missing values, engineer features, and prepare a clean dataset ready for machine learning.

## 📌 Objectives
- Load and inspect the dataset  
- Identify and treat missing values  
- Perform exploratory data analysis  
- Create new features such as FamilySize  
- Export a cleaned version of the dataset  

## 🛠️ Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

## 📊 Key Steps in Analysis

### **1. Data Overview**
- Dataset shape: 891 rows × 12 columns  
- Initial checks for data types, missing values, and structure  

### **2. Missing Value Handling**
- Filled `Embarked` with most frequent value  
- Noted large missing data in `Cabin`  
- Cleaned other fields for consistent analysis  

### **3. Feature Engineering**
- Created **FamilySize = SibSp + Parch + 1**  
- Added cleaned and filled categorical columns  
- Prepared selected columns for modeling  

### **4. Visualizations**
- Survival analysis by Sex, Pclass, Age groups, and Embarked  
- Distribution plots and correlation heatmap  

### **5. Cleaned Dataset**
Final dataset includes:

