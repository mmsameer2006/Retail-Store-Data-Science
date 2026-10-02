# 🛒 Retail Store Data Science Project

## 📌 Project Overview

This project focuses on analyzing a real-world retail store sales dataset using Python and Data Science techniques.

The project follows an end-to-end data science workflow including **data cleaning, exploratory data analysis, data visualization, machine learning, model evaluation, and business insights**.

The main objective is to understand retail sales patterns and build a machine learning model to predict total customer spending.

---

## 🎯 Project Objectives

* Clean and preprocess retail sales data
* Handle missing values and duplicate records
* Perform Exploratory Data Analysis (EDA)
* Analyze sales by category, location, and payment method
* Identify relationships between numerical variables
* Visualize important sales trends
* Build a machine learning model for sales prediction
* Evaluate model performance
* Generate meaningful business insights

---

## 📂 Dataset

The project uses a retail store sales dataset containing transaction-level information.

### Important Columns

| Column           | Description                  |
| ---------------- | ---------------------------- |
| Transaction Date | Date of the transaction      |
| Item             | Product purchased            |
| Category         | Product category             |
| Price Per Unit   | Price of one unit            |
| Quantity         | Number of units purchased    |
| Total Spent      | Total transaction amount     |
| Payment Method   | Payment method used          |
| Location         | Store/location information   |
| Discount Applied | Whether discount was applied |

---

# Data Cleaning & Visualization

The first stage focuses on preparing the raw retail dataset for analysis.

### Data Cleaning

* Checked dataset structure
* Checked missing values
* Checked duplicate records
* Converted transaction dates into datetime format
* Filled missing product values
* Filled missing price and quantity values
* Calculated missing total spending values
* Removed duplicate records

### Visualizations

The following visualizations were created:

* Sales by Category
* Payment Method Distribution
* Location Analysis
* Quantity Distribution
* Price vs Quantity
* Correlation Heatmap

### Notebook

```text
Data cleaning and visualization/
└── Retail_Store_sales_data.ipynb
```

---

# Predictive Modeling

Machine Learning was applied to predict **Total Spent**.

### Features Used

```text
Price Per Unit
Quantity
```

### Target Variable

```text
Total Spent
```

### Machine Learning Algorithm

```text
Random Forest Regression
```

### Model Evaluation

The model was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

### Visualizations

* Actual vs Predicted Sales
* Feature Importance

### Notebook

```text
Predictive Modeling/
└── predictive_modeling.ipynb
```

---

# Exploratory Data Analysis

EDA was performed to discover patterns and trends in the retail dataset.

### Analysis Performed

* Dataset overview
* Statistical summary
* Missing value analysis
* Category analysis
* Sales analysis
* Payment method analysis
* Location analysis
* Quantity distribution
* Total spending distribution
* Price vs Quantity relationship
* Correlation analysis
* Monthly sales trend
* Average spending by category
* Discount analysis
* Category-wise spending distribution
* Top 10 products by sales

### Notebook

```text
Exploratory_data_analysis/
└── exploratory_data_analysis.ipynb
```

---

#  Real-World Retail Data Science Project

This section combines the complete data science workflow into a real-world retail analytics project.

### Workflow

```text
Raw Data
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Data Visualization
   ↓
Correlation Analysis
   ↓
Machine Learning
   ↓
Model Evaluation
   ↓
Business Insights
   ↓
Conclusion
```

### Key Analysis

The project analyzes:

* Product category performance
* Monthly sales trends
* Payment preferences
* Location-wise transactions
* Price and quantity relationships
* Total customer spending
* Important prediction features

### Machine Learning

A **Random Forest Regression** model is used to predict total spending based on sales-related features.

### Notebook

```text
Real World Project
└── Retail_Store_Real_World_Analysis.ipynb
```

---

# 📊 Visualizations

The project contains multiple visualizations, including:

* Sales by Category
* Payment Method Distribution
* Location Analysis
* Monthly Sales Trend
* Quantity Distribution
* Total Spending Distribution
* Correlation Heatmap
* Actual vs Predicted Sales
* Feature Importance
* Top 10 Products
* Category-wise Sales

All generated charts are stored inside:

```text
visualizations/
```

---

# 🧰 Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

### Development Tools

* Jupyter Notebook
* VS Code
* Git
* GitHub

---

# 📁 Project Structure

```text
Retail-Store-Sales-Data Science/
│
├── data/
│   ├── raw/
│   │   └── retail_store_sales.csv
│   │
│   └── cleaned/
│       ├── retail_store_sales_cleaned.csv
│       ├── model_predictions.csv
│       └── eda_summary.csv
│
├── Data cleaning and visualization/
│   └── Retail_Store_sales_data.ipynb
│
├── Predictive Modeling/
│   └── predictive_modeling.ipynb
│
├── Exploratory data analysis/
│   └── exploratory_data_analysis.ipynb
│
├── Real World Project/
│   └── Retail_Store_Real_World_Analysis.ipynb
│
├── visualizations/
│   ├── Multi visualization.png
└── README.md
```

---

# 📈 Model Evaluation

The Random Forest Regression model is evaluated using standard regression metrics:

### MAE

Measures the average absolute difference between actual and predicted values.

### MSE

Measures the average squared prediction error.

### RMSE

Measures prediction error in the same unit as the target variable.

### R² Score

Measures how well the model explains the variation in the target variable.

> Model scores should be updated with the actual values generated when the notebook is executed.

---

# 💡 Business Insights

The analysis can help a retail business understand:

* Which product categories generate more sales
* How sales change over time
* Which payment methods are commonly used
* Which locations have higher transaction activity
* How price and quantity relate to total spending
* Which features contribute more to sales prediction
* How machine learning can support retail sales analysis

---

# 🎓 Learning Outcomes

Through this project, the following Data Science skills were practiced:

* Data preprocessing
* Data cleaning
* Missing value handling
* Duplicate removal
* Exploratory Data Analysis
* Statistical analysis
* Data visualization
* Correlation analysis
* Feature analysis
* Machine Learning
* Regression modeling
* Model evaluation
* Business interpretation
* Git and GitHub project management

---

# 🚀 Future Improvements

The project can be further improved by:

* Adding more customer-related features
* Using advanced feature engineering
* Comparing Linear Regression, Decision Tree, and Random Forest
* Hyperparameter tuning
* Adding time-series sales forecasting
* Building an interactive Power BI dashboard
* Creating a Streamlit web application
* Deploying the prediction model

---

# 👨‍💻 Author

** M Mohamed Sameer**

Aspiring Data Analyst / Data Scientist

### Skills

```text
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
SQL
Power BI
Git
GitHub
```

---

# ⭐ Conclusion

This Retail Store Data Science Project demonstrates how Python and Machine Learning can be used to solve a real-world retail analytics problem.

The project covers the complete workflow from **raw data cleaning to exploratory analysis, visualization, prediction, model evaluation, and business insights**.

It provides practical experience in applying Data Science techniques to real-world business data.
