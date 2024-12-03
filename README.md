# Exploratory Data Analysis: Cardiographic Dataset

## Overview
This project performs a comprehensive Exploratory Data Analysis (EDA) on the "cardiographic.csv" dataset to uncover patterns, relationships, and trends in the data. The goal is to gain insights into fetal and maternal health indicators through statistical summaries, visualizations, and data manipulation techniques.

## Table of Contents
* Project Description
* Dataset Details
* Technologies Used
* Steps Performed
* Results and Insights

## Project Description
The dataset includes features related to fetal heart rate (FHR) and uterine contractions, among others. This EDA project analyzes these variables to understand their distribution, relationships, and potential implications for fetal health.

## Dataset Details
* Dataset Name: cardiographic.csv
* Features:
* LB: Baseline Fetal Heart Rate (FHR).
* AC: Accelerations in FHR, a sign of fetal well-being.
* FM: Fetal Movements detected by the monitor.
* UC: Uterine Contractions, influencing FHR patterns.
* DL: Decelerations (Late), indicating possible fetal distress.
* DS: Decelerations (Short).
* DP: Decelerations (Prolonged).
* ASTV: Percentage of time with abnormal short-term variability.
* MSTV: Mean value of short-term variability.
* ALTV: Percentage of time with abnormal long-term variability.
* MLTV: Mean value of long-term variability.

## Technologies Used
* Programming Language: Python
* Libraries:
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Platform: Jupyter Notebook
  
## Steps Performed
1. Data Cleaning and Preparation:

Loaded the dataset into a Pandas DataFrame.
Handled missing values through imputation or removal.
Fixed data type inconsistencies (e.g., converting strings to numerical types).
Detected and treated outliers to improve data quality.

2. Statistical Summary:

Calculated central tendency (mean, median) and dispersion (standard deviation, interquartile range).
Highlighted interesting findings, such as skewed distributions or outliers.

3. Data Visualization:

Plotted histograms and boxplots to understand numerical distributions.
Used bar charts or pie charts for categorical variable frequencies.
Created scatter plots and correlation heatmaps to explore variable relationships.
Advanced visualizations like pair plots and violin plots for deeper analysis.

4. Pattern Recognition and Insights:

Identified correlations and discussed their implications.
Analyzed potential trends in temporal data if applicable.

5. Conclusion:

Summarized key findings and their impact on fetal health monitoring.
Provided recommendations for further analysis or decision-making.

## Results and Insights
* Key Findings:
* Relationships between FHR and uterine contractions.
* Variability patterns (short-term and long-term) as indicators of fetal health.
* Identification of abnormal patterns that could signify distress.
* Visual Insights:
* Scatter plots showed strong correlations between [specific features].
* Heatmaps revealed potential clustering among certain variables.
