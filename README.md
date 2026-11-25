# 🛒 RetailPulse – Retail Sales & Customer Analytics System

### End-to-End Data Analytics, Customer Segmentation & Sales Forecasting Project

## 📌 Project Overview

RetailPulse is an end-to-end Retail Data Analytics project developed to analyze retail sales, customer purchasing behaviour, product performance and revenue trends.

The project combines Python, Machine Learning, Excel and Power BI to transform raw retail data into meaningful business insights.

It covers the complete analytics workflow, including data cleaning, exploratory data analysis (EDA), RFM analysis, customer segmentation using K-Means clustering, sales forecasting and interactive Power BI dashboards.

## 🎯 Project Objectives

- Analyze retail sales and revenue performance.
- Understand customer purchasing behaviour.
- Identify high-value and inactive customers.
- Perform customer segmentation using Machine Learning.
- Analyze product and country-wise sales.
- Forecast revenue for the next three months.
- Present business insights through Power BI dashboards.

## 🛠️ Technologies Used

| Technology       | Purpose                         |
| ---------------- | ------------------------------- |
| Python           | Data analysis and preprocessing |
| Pandas           | Data manipulation and cleaning  |
| NumPy            | Numerical operations            |
| Matplotlib       | Data visualization              |
| Seaborn          | Statistical visualization       |
| Scikit-learn     | Machine Learning                |
| K-Means          | Customer segmentation           |
| PCA              | Cluster visualization           |
| Statsmodels      | Sales forecasting               |
| Excel            | Dataset management              |
| Power BI         | Interactive dashboards          |
| Jupyter Notebook | Development environment         |

## 📊 Project Workflow

### 1. Data Loading & Cleaning

- Load retail dataset using Pandas.
- Inspect dataset structure and data types.
- Handle missing values.
- Remove duplicate records.
- Convert date columns into datetime format.
- Handle cancelled transactions and invalid records.

### 2. Exploratory Data Analysis (EDA)

- Monthly and yearly sales analysis.
- Revenue and order analysis.
- Customer spending analysis.
- Repeat customer analysis.
- Top-performing products.
- Country-wise sales analysis.
- Correlation analysis.
- Business insights and visualizations.

### 3. RFM Analysis

RFM stands for:

- Recency: How recently a customer purchased.
- Frequency: How often a customer purchased.
- Monetary: How much a customer spent.

Additional steps:

- RFM feature engineering.
- Outlier detection using IQR.
- Log transformation.
- Feature scaling using StandardScaler.

### 4. Customer Segmentation using K-Means

Machine Learning is used to divide customers into three segments:

- High-Value Customers
- Occasional Customers
- Inactive Customers

Methods used:

- Elbow Method
- Silhouette Score
- K-Means Clustering
- PCA Visualization
- Cluster Analysis

### 5. Model Evaluation

The clustering model is evaluated using:

- Silhouette Score
- Davies-Bouldin Score
- Calinski-Harabasz Score

### 6. Sales Prediction & Forecasting

A Holt-Winters Exponential Smoothing model is used for three-month revenue forecasting.

Evaluation metrics:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- MAPE (Mean Absolute Percentage Error)

The forecast results are exported to CSV for Power BI visualization.

## 📈 Power BI Dashboards

The project includes two interactive Power BI dashboards.

**Dashboard 1**

- Retail sales analysis
- Revenue performance
- Customer analytics
- Business insights

**Dashboard 2**

- Revenue forecasting
- Monthly revenue trends
- Predicted sales analysis

Dashboard screenshots and design assets are included in the repository.

## 📁 Key Project Outputs

- RetailPulse_Cleaned.csv
- customer_rfm_final.csv
- customer_segmentation_final.csv
- Sales_Forecast_Predictions.csv

## ⚙️ Installation & Setup

Clone the repository:

```bash
git clone https://github.com/Shubham05-tech/Data-Analytics-Portfolio.git
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels openpyxl jupyter
```

Open Jupyter Notebook:

```bash
jupyter notebook
```

Open the RetailPulse analysis notebook and run the cells in sequence.

Note: Update dataset file paths according to your local folder structure before running the notebook.

## 💡 Skills Demonstrated

- Data Cleaning & Preprocessing
- Exploratory Data Analysis
- Statistical Analysis
- Feature Engineering
- Customer Segmentation
- Unsupervised Machine Learning
- Time Series Forecasting
- Data Visualization
- Power BI Dashboard Development
- Business Intelligence

## 👨‍💻 Author

**Shubham Pal**

MCA – Artificial Intelligence & Data Science

GitHub: [https://github.com/Shubham05-tech](https://github.com/Shubham05-tech)

Portfolio: [https://shubham05-tech.github.io/portfolio/](https://shubham05-tech.github.io/portfolio/)

---

⭐ If you find this project useful, feel free to explore the repository and give it a star!

**Thank you for visiting RetailPulse!**
