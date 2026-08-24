# SpaceX Falcon 9 First Stage Landing Prediction 🚀

## Overview

This project is an end-to-end **Data Science and Machine Learning capstone project** focused on predicting whether the first stage of a SpaceX Falcon 9 rocket will successfully land.

SpaceX's ability to recover and reuse Falcon 9 first stages significantly reduces launch costs. Predicting landing success can therefore provide valuable insights into launch cost estimation and competitive analysis in the commercial space industry.

The project demonstrates a complete data science workflow, from **data collection and web scraping to exploratory data analysis, visualization, dashboard development, and machine learning prediction**.

---

## Project Objectives

The main objectives of this project are to:

* Collect SpaceX launch data using APIs
* Scrape additional launch information from web sources
* Clean and prepare the data
* Perform exploratory data analysis
* Analyze the data using SQL
* Create visualizations to identify patterns and relationships
* Build an interactive dashboard
* Develop machine learning models
* Predict Falcon 9 first-stage landing success
* Evaluate and compare model performance

---

## Technologies & Tools

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Plotly**
* **Dash**
* **Scikit-learn**
* **SQL**
* **REST APIs**
* **BeautifulSoup**
* **Jupyter Notebook**

---

## Project Workflow

The project consists of eight labs covering the complete data science workflow.

### Lab 1 — Collecting the Data

**File:** `01-Collecting-the-Data.ipynb`

Collected Falcon 9 launch data using the SpaceX API and performed initial data cleaning and formatting.

**Key concepts:**

* REST API requests
* JSON data
* API data extraction
* Data cleaning
* Pandas

---

### Lab 2 — Web Scraping

**File:** `02-Web-Scraping.ipynb`

Collected additional Falcon 9 launch information through web scraping.

**Key concepts:**

* Web scraping
* BeautifulSoup
* HTML parsing
* Data extraction
* Data preparation

---

### Lab 3 — Data Wrangling

**File:** `03-Data-Wrangling.ipynb`

Cleaned and transformed the collected data and prepared the target variable for machine learning.

**Key concepts:**

* Missing-value handling
* Data transformation
* Feature selection
* One-hot encoding
* Target variable creation

---

### Lab 4 — Exploratory Data Analysis with SQL

**File:** `04-EDA-with-SQL.ipynb`

Used SQL queries to investigate the SpaceX dataset and identify relationships between launch characteristics and landing outcomes.

**Key concepts:**

* SQL queries
* Filtering
* Aggregation
* Grouping
* Ordering
* Data analysis

---

### Lab 5 — Exploratory Data Analysis with Visualization

**File:** `05-EDA-with-Visualization.ipynb`

Created visualizations to understand patterns in SpaceX launches and investigate factors related to landing success.

**Visualizations include:**

* Scatter plots
* Bar charts
* Pie charts
* Launch-site analysis
* Payload analysis
* Landing outcome analysis

---

### Lab 6 — Interactive Visual Analytics

**File:** `06-Interactive-Visual-Analytics.ipynb`

Developed interactive visualizations to explore SpaceX launch data and investigate relationships between different variables.

**Key concepts:**

* Plotly
* Interactive charts
* Data filtering
* Visual analytics
* Interactive exploration

---

### Lab 7 — Interactive Dashboard

**File:** `07-Interactive-Dashboard-with-Plotly-and-Dash.py`

Built an interactive dashboard using **Plotly and Dash** to analyze Falcon 9 launch records.

The dashboard allows users to interactively explore launch data and investigate factors associated with first-stage landing success.

**Technologies:**

* Plotly
* Dash
* Python
* Interactive visualization
* Dashboard development

---

### Lab 8 — Predictive Analysis

**File:** `08-Predictive-Analysis.ipynb`

Developed machine learning models to predict whether the Falcon 9 first stage would successfully land.

**Machine learning workflow:**

1. Prepare the dataset
2. Select relevant features
3. Split the data into training and testing sets
4. Train classification models
5. Evaluate model performance
6. Compare different models
7. Select the best-performing model

**Models explored include classification algorithms such as:**

* Logistic Regression
* Support Vector Machine
* Decision Tree
* K-Nearest Neighbors

---

## Key Data Science Skills Demonstrated

This project demonstrates practical experience in:

### Data Collection

* REST APIs
* Web scraping
* JSON data
* HTML parsing

### Data Analysis

* Pandas
* NumPy
* SQL
* Exploratory Data Analysis

### Data Visualization

* Matplotlib
* Seaborn
* Plotly
* Interactive visualizations

### Dashboard Development

* Plotly Dash
* Interactive filters
* Data-driven dashboards

### Machine Learning

* Classification
* Feature engineering
* Train/test splitting
* Model evaluation
* Predictive analysis

---

## Project Structure

```text
SpaceX-Falcon-9-Landing-Prediction/
│
├── notebooks/
│   ├── 01-Collecting-the-Data.ipynb
│   ├── 02-Web-Scraping.ipynb
│   ├── 03-Data-Wrangling.ipynb
│   ├── 04-EDA-with-SQL.ipynb
│   ├── 05-EDA-with-Visualization.ipynb
│   ├── 06-Interactive-Visual-Analytics.ipynb
│   ├── 07-Interactive-Dashboard-with-Plotly-and-Dash.py
│   └── 08-Predictive-Analysis.ipynb
│
├── images/
│   ├── Scatter-Plot.png
│   └── Pie-Chart.png
│
└── README.md
```

---

## Results

The project combines exploratory analysis, interactive visualization, dashboard development, and machine learning to investigate the factors associated with Falcon 9 first-stage landing success.

The final predictive analysis demonstrates how historical launch data can be used to build classification models capable of estimating landing outcomes.

---

## Learning Outcomes

Through this project, I gained practical experience in the complete data science lifecycle:

**Data Collection → Data Wrangling → EDA → SQL → Visualization → Interactive Dashboard → Machine Learning → Prediction**

The project strengthened my ability to work with real-world datasets and apply Python, SQL, data visualization, and machine learning techniques to solve a practical prediction problem.

---

## Acknowledgment

This project was completed as part of the **IBM Data Science Professional Certificate Capstone Project**.
