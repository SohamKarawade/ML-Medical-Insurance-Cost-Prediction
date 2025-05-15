# Medical Insurance Cost Prediction using Machine Learning

This project performs an end-to-end analysis and prediction of medical insurance costs using Python in a Jupyter Notebook. It includes Exploratory Data Analysis (EDA), data visualization, preprocessing, and implementation of multiple regression models to predict charges based on individual attributes.

---

## Dataset

**Source**: Kaggle / Public Medical Insurance Dataset  
**File**: `insurance.csv`  
**Columns**:
- `age`: Age of the individual  
- `sex`: Gender  
- `bmi`: Body Mass Index  
- `children`: Number of dependents  
- `smoker`: Smoking status  
- `region`: Residential region  
- `charges`: Medical insurance cost (target)

---

## Project Overview

The project is divided into 3 major stages:

---

### Stage 1: Exploratory Data Analysis (EDA)

- Overview of data types and null values  
- Summary statistics of features  
- Correlation heatmap  
- Distribution of medical charges  

---

### Stage 2: Visualization

- Charges by age, gender, and smoking status  
- BMI vs charges (highlighting obesity impact)  
- Region-wise charge comparison  
- Children vs cost impact  

---

### Stage 3: Machine Learning Modeling

- **Data Preprocessing**: Label Encoding, Feature Scaling  
- **Models Used**:
  - Linear Regression  
  - Random Forest Regressor  
  - Polynomial Regression  
- **Model Evaluation**:
  - R² Score  
  - Mean Squared Error (MSE)  
- **Comparison of model accuracy and selection of best-fit model**

---
