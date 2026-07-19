# SpaceX Falcon 9 Landing Prediction

## Overview

This repository contains my final project for the IBM Applied Data Science Capstone course.

The goal of this project is to analyze historical Falcon 9 launch data and build machine learning models capable of predicting whether the first stage booster will successfully land. Since SpaceX reuses its boosters to reduce launch costs, understanding the factors behind successful landings can provide valuable business insights.

The project follows the complete data science process, from collecting raw data to building predictive models.

---

## Project Workflow

### Data Collection

Launch data was collected from multiple sources:

- SpaceX REST API
- Wikipedia launch records through web scraping

The collected data was combined into a structured dataset for analysis.

---

### Data Wrangling

The dataset was cleaned and prepared by:

- Handling missing values
- Removing unnecessary information
- Formatting columns
- Creating variables needed for later analysis

---

### Exploratory Data Analysis

Several visualizations were created to better understand the dataset, including relationships between:

- Launch sites
- Payload mass
- Booster versions
- Flight numbers
- Mission outcomes

These analyses helped identify trends associated with successful booster landings.

---

### SQL Analysis

The cleaned dataset was imported into an IBM Db2 database where SQL queries were used to answer questions about launch history, launch sites, payloads, and mission success.

---

### Interactive Mapping

Using Folium, interactive maps were created to visualize:

- SpaceX launch locations
- Nearby infrastructure
- Launch outcomes

These maps provided additional geographic context for the launch data.

---

### Interactive Dashboard

A Plotly Dash dashboard was developed that allows users to:

- Filter launches by site
- Select payload ranges
- View launch success rates
- Explore relationships between payload and landing success

---

### Machine Learning

Several classification algorithms were trained and compared, including:

- Logistic Regression
- Support Vector Machine
- Decision Tree
- K Nearest Neighbors

GridSearchCV was used to optimize model parameters before evaluation.

---

## Results

The models successfully predicted Falcon 9 landing outcomes using historical launch data.

| Model | Test Accuracy |
|-------|--------------:|
| Decision Tree | **94.44%** |
| Support Vector Machine | 83.33% |
| K-Nearest Neighbors | 83.33% |

The Decision Tree classifier got the highest overall accracy.

---

## Technologies

- Python
- Pandas
- NumPy
- BeautifulSoup
- Matplotlib
- Seaborn
- Plotly Dash
- Folium
- Scikit learn
- SQL
- Jupyter Notebook

---

## Repository Contents

- Data collection notebooks
- Web scraping notebook
- Data wrangling notebook
- Exploratory data analysis notebooks
- SQL analysis notebook
- Folium mapping notebook
- Plotly Dash application
- Machine learning notebook
- Supporting datasets

---

## Key Takeaways

This project demonstrates an end-to-end data science workflow by combining data collection, cleaning, visualization, SQL, interactive dashboards, geographic analysis, and machine learning to predict Falcon 9 landing success.

---

## Author

**Abrar Alam**
