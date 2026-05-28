# Exploratory Data Analysis on University Students Performance Dataset

## Project Overview
This project performs Exploratory Data Analysis (EDA) on a dataset containing information about university students. The goal is to uncover insights and patterns related to:

* Academic performance
* Study habits
* Demographic factors
* Test preparation
* Extracurricular indicators
The analysis includes data cleaning, transformation, visualization, statistical analysis, outlier detection, and hypothesis testing using Python.

# Objective

Conduct EDA on student performance data to identify trends, correlations, and statistical relationships between variables affecting academic scores.

# Dataset

Dataset Used: `StudentsPerformance.csv`
The dataset contains information such as:
* Gender
* Race/Ethnicity
* Parental level of education
* Lunch type
* Test preparation course
* Math score
* Reading score
* Writing score

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Jupyter Notebook
* 
# Steps Performed

## 1. Data Collection and Loading

* Loaded dataset using Pandas
* Inspected dataset structure using:

  * `head()`
  * `describe()`

## 2. Data Cleaning

* Checked missing values using `isnull()`
* Handled missing values using forward fill method
* Verified and corrected data types

## 3. Data Transformation

* Encoded categorical variables
* Converted gender categories into numerical format

## 4. Data Visualization

Created multiple visualizations including:

* Bar charts
* Histograms
* Box plots
* Scatter plots
* Correlation heatmaps
* Distribution plots

Visualization libraries used:

* Matplotlib
* Seaborn

## 5. Descriptive Statistics

Calculated:

* Mean
* Median
* Standard deviation
* Correlation coefficients

## 6. Pattern and Relationship Analysis

Performed:

* Correlation analysis
* Grouped statistical analysis
* Multivariate analysis

## 7. Outlier Detection

Used Interquartile Range (IQR) method for identifying outliers.

Formula used:

IQR = Q3 - Q1

Outliers detected using:

* Lower Bound = Q1 - 1.5 × IQR
* Upper Bound = Q3 + 1.5 × IQR

## 8. Hypothesis Testing

Performed Independent T-Test using SciPy to compare math scores between male and female students.

Hypothesis:

* Null Hypothesis (H0): No difference in math scores
* Alternative Hypothesis (H1): Significant difference exists

## 9. Findings and Insights

Key insights obtained from analysis include:

* Reading and writing scores show strong positive correlation.
* Students completing test preparation courses generally perform better.
* Distribution of scores varies across demographic groups.
* Outliers were identified in math score distributions.

# Sample Visualizations

The project includes:

* Correlation Heatmaps
* Boxplots
* Distribution Plots
* Scatterplots
* Comparative Bar Charts


# Project Structure

```text
Student-Performance-EDA/
│
├── StudentsPerformance.csv
├── EDA_Project.ipynb
├── README.md
├── requirements.txt
└── screenshots/
```

# How to Run the Project

## 1. Clone Repository

```bash
git clone <repository-link>
```

## 2. Install Dependencies

```bash
pip install -r requirements.txt
```

## 3. Run Jupyter Notebook

```bash
jupyter notebook
```

Open:
`EDA_Project.ipynb`

# Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Data Visualization
* Statistical Analysis
* Correlation Analysis
* Hypothesis Testing
* Outlier Detection
* Python Programming

# Future Improvements

* Build interactive dashboard using Streamlit or Tableau
* Apply Machine Learning models
* Deploy visualization dashboard online
# Conclusion
This project demonstrates how Exploratory Data Analysis can uncover meaningful insights from educational datasets using Python-based data analysis and visualization techniques.
