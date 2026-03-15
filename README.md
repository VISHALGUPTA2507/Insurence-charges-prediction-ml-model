# Insurance Charges Prediction using Machine Learning

## Project Overview
This project focuses on building a machine learning regression model to predict medical insurance charges based on demographic and lifestyle attributes such as age, BMI, smoking habits, and region. The objective is to analyze how different factors influence healthcare costs and develop a predictive model using Python and data science libraries.

The project demonstrates a complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

---

# Dataset
The dataset used in this project contains information about individuals and their medical insurance charges.

### Features
- **age** – Age of the insurance policy holder  
- **sex** – Gender of the individual  
- **bmi** – Body Mass Index indicating body fat  
- **children** – Number of dependents covered by insurance  
- **smoker** – Smoking status (yes/no)  
- **region** – Residential region  
- **charges** – Medical insurance cost billed to the individual (target variable)

The dataset contains **1338 records and 7 features**.

---

# Project Workflow

## 1. Data Collection
The dataset is loaded using the **Pandas library** and stored in a DataFrame for analysis.

## 2. Data Preprocessing
Data preprocessing ensures the dataset is suitable for machine learning models.

Steps performed:
- Checking for missing values
- Converting categorical variables to numerical format
- Ensuring proper data types

## 3. Data Cleaning
Data cleaning improves data quality by:
- Removing inconsistencies
- Handling duplicates
- Ensuring uniform data formatting

## 4. Exploratory Data Analysis (EDA)
EDA is performed to understand relationships between variables.

Visualizations include:
- Distribution plots
- Scatter plots
- Correlation heatmaps
- Feature comparison graphs

EDA helps identify important factors affecting insurance charges.

## 5. Feature Engineering
Categorical variables such as **sex, smoker, and region** are encoded into numerical values so they can be used in machine learning models.

## 6. Train-Test Split
The dataset is divided into:

- **Training set (80%)** – used to train the model  
- **Testing set (20%)** – used to evaluate model performance

## 7. Model Training
A regression algorithm is used to learn the relationship between input features and insurance charges.

## 8. Model Evaluation
The model performance is evaluated using regression metrics such as:

- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**

These metrics measure how accurately the model predicts insurance costs.

---

# Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Development Environment
- Jupyter Notebook
- Anaconda

---

# Project Structure

```
Insurence-charges-prediction-ml-model
│
├── insurance.csv
├── project1.ipynb
└── README.md
```

---

# Results
The trained machine learning model successfully predicts insurance charges based on input features. The analysis also highlights important factors such as **age, BMI, and smoking habits**, which significantly influence medical costs.

---

# Future Improvements
Possible improvements for this project include:

- Testing multiple regression algorithms
- Hyperparameter tuning
- Building a web interface using **Streamlit**
- Deploying the model using **Flask or FastAPI**

---

# Author
**Potta Vishalgupta**
