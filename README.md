# Elevate Labs Data Analyst Internship - Task 5: Exploratory Data Analysis (EDA)

## Project Overview

This repository contains the solution for Task 5 of the Elevate Labs Data Analyst Internship, focusing on Exploratory Data Analysis (EDA) of the Titanic dataset. The objective was to extract meaningful insights from the data through visual and statistical exploration.

## [cite_start]Objective 

[cite_start]The primary objective of this task was to extract insights from a dataset using visual and statistical exploration techniques. This involved understanding data distributions, identifying relationships between variables, and uncovering trends and anomalies.

## Dataset

* **Dataset Used:** Titanic Dataset (`train.csv`)

    The dataset contains information about passengers on the Titanic, including demographics (age, sex), travel details (fare, class, embarked port, number of siblings/spouses and parents/children aboard), and most importantly, their survival status.

## [cite_start]Tools & Technologies 

* **Programming Language:** Python
* **Libraries:**
    * [cite_start]Pandas (for data manipulation and analysis) 
    * [cite_start]Matplotlib (for basic plotting) 
    * [cite_start]Seaborn (for advanced statistical data visualization) 
* **Environment:** Jupyter Notebook

## [cite_start]Key Steps Performed 

The EDA process followed these key steps, as guided by the task:

1.  **Initial Data Inspection:**
    * [cite_start]Used `.info()` to get a summary of the DataFrame, including data types and non-null values.
    * [cite_start]Used `.describe()` to obtain descriptive statistics for numerical columns.
    * [cite_start]Used `.value_counts()` on categorical columns to understand their distribution.
2.  **Data Cleaning & Preprocessing:**
    * Identified and handled missing values (e.g., in 'Age' and 'Embarked' columns).
    * Dropped irrelevant columns or columns with excessive missing data (e.g., 'Cabin').
3.  **Univariate Analysis:**
    * [cite_start]Plotted histograms for numerical features (e.g., 'Age', 'Fare') to visualize their distributions.
4.  **Bivariate Analysis:**
    * [cite_start]Created boxplots to compare numerical features across different categories (e.g., 'Fare' by 'Pclass').
    * [cite_start]Generated scatterplots to explore relationships between two numerical variables, often colored by a third categorical variable (e.g., 'Age' vs. 'Fare' colored by 'Survived').
    * [cite_start]Used `sns.pairplot()` to visualize relationships between multiple numerical variables and their individual distributions.
5.  **Correlation Analysis:**
    * [cite_start]Generated a correlation heatmap using `sns.heatmap()` to visualize the correlation matrix of numerical features, identifying strong positive or negative relationships.
6.  **Observation and Interpretation:**
    * [cite_start]Wrote observations for each visual.
    * [cite_start]Identified relationships and trends from the visualizations.
7.  **Summary of Findings:**
    * [cite_start]Provided a concise summary of all key insights extracted from the data.



## Deliverables

* `titanic_eda_task5.ipynb`: Jupyter Notebook containing all the Python code for EDA, visualizations, and observations.
* `titanic_eda_report.pdf`: A PDF report of the findings, exported directly from the Jupyter Notebook.
* `train.csv`: The dataset used for the analysis.
* `README.md`: This file, summarizing the project.

