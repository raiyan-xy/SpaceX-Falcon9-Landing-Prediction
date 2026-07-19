# Applied Data Science Capstone

## Project Overview

This project explores the launch history of SpaceX Falcon 9 rockets and builds machine learning models to predict whether the first stage booster will successfully land. Since SpaceX is able to reuse its boosters, successful landings help reduce launch costs. Predicting landing success can provide useful insights for estimating mission costs and analyzing launch performance.

---

## Project Objectives

Throughout this project, I completed the full data science workflow, including:

- Collecting launch data from the SpaceX API
- Gathering additional launch information through web scraping
- Cleaning and preparing the dataset for analysis
- Performing exploratory data analysis (EDA)
- Writing SQL queries to analyze launch data
- Creating interactive maps with Folium
- Building an interactive dashboard using Plotly Dash
- Training and evaluating multiple machine learning classification models

---

## Technologies Used

- Python
- Pandas
- NumPy
- BeautifulSoup
- Matplotlib
- Seaborn
- Plotly Dash
- Folium
- Scikit-learn
- SQL (IBM Db2)
- Jupyter Notebook

---

## Project Workflow

### 1. Data Collection
- Retrieved launch data using the SpaceX REST API
- Collected additional launch records through web scraping

### 2. Data Preparation
- Cleaned missing values
- Organized and transformed the data
- Prepared the dataset for analysis

### 3. Exploratory Data Analysis
- Examined launch trends
- Compared launch sites, payloads, booster versions, and outcomes
- Created visualizations to better understand the data

### 4. SQL Analysis
- Loaded the dataset into an IBM Db2 database
- Used SQL queries to answer business and analytical questions

### 5. Interactive Visualizations
- Built interactive maps with Folium
- Developed a Plotly Dash dashboard for exploring launch success by launch site and payload

### 6. Machine Learning
- Standardized the data
- Split the dataset into training and testing sets
- Trained several classification models
- Compared model performance to identify the most accurate predictor

---

## Results

Several machine learning models were evaluated to predict Falcon 9 landing success.

| Model | Accuracy |
|--------|---------:|
| Decision Tree | 94.44% |
| Support Vector Machine | 83.33% |
| K-Nearest Neighbors | 83.33% |

The Decision Tree model achieved the highest prediction accuracy and produced the best overall performance.

---

## Repository Contents

- Jupyter notebooks
- Python scripts
- Datasets
- Interactive dashboard
- Maps and visualizations
- Final presentation

---

## Conclusion

This capstone project combines data collection, cleaning, visualization, SQL analysis, and machine learning to study Falcon 9 launches. The final model demonstrates how historical launch data can be used to predict landing success, showcasing a complete end-to-end data science workflow.

---

## Author

**Abrar Alam**
