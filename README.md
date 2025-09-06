# COVID-19 Data Analysis Project

This repository contains a comprehensive data analysis project using the **[`covid_19_data.csv`](./covid_19_data.csv)** dataset.  
The goal of this project is to apply **data cleaning**, **exploratory data analysis (EDA)**, and **basic machine learning** concepts to understand and visualize global COVID-19 trends.

---

## 📊 Dataset Information

The dataset used in this project-**[`covid_19_data.csv`](./covid_19_data.csv)**-was sourced from Kaggle:  
👉 [Novel Corona Virus 2019 Dataset (by Sudalai Rajkumar)](https://www.kaggle.com/datasets/sudalairajkumar/novel-corona-virus-2019-dataset)

It contains global case reports of COVID-19, including:

- **Observation Date** → Date when the record was logged  
- **Province/State** → Sub-region
- **Country/Region** → Country name  
- **Last Update** → Time when the record was last updated  
- **Confirmed** → Number of confirmed COVID-19 cases  
- **Deaths** → Number of deaths caused by COVID-19  
- **Recovered** → Number of recoveries reported  

### 📌 Notes on the Dataset
- The dataset was **sourced from Kaggle’s COVID-19 repository**.  
- It is regularly updated with global case data.  
- Data may contain **missing or inconsistent values**, which were cleaned during the preprocessing step in this project.  
- Column names were standardized for easier handling in Python (e.g., lowercase, no spaces).  

---

## 🚀 Key Features

- **Data Cleaning:**  
  - Handled missing values  
  - Ensured correct data types  
  - Standardized column names for consistency  

- **Exploratory Data Analysis (EDA):**  
  - Aggregations to summarize the dataset  
  - Top countries by confirmed cases  
  - Mortality and recovery rates calculation  

- **Unsupervised Learning (K-Means Clustering):**  
  - Grouped countries with similar case profiles  
  - Identified hidden patterns in the data  

- **Data Visualization:**  
  - Plots generated using **matplotlib** and **seaborn**  
  - Scatter plot for visualizing clusters  
  - Informative charts for better understanding  

---

## ⚡ Getting Started

### 1. Clone this repository
```bash
git clone https://github.com/okayprashant/covid19-data-analysis.git
cd covid19-data-analysis
```
## 2. Install Dependencies

Make sure you have **Python 3.x** installed. Install the required libraries using pip:
bash
pip install pandas matplotlib seaborn scikit-learn
