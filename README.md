# Data-Cleaning-and-Preprocessing
This repository contains code and data files for cleaning, preprocessing, and visualizing the classic Titanic dataset using Python, with a focus on NumPy and Pandas workflows.

**Project Overview**
Dataset: The original dataset (Titanic-Dataset.csv) includes passenger data from the Titanic disaster, widely used in machine learning and data analysis tutorials.

Goal: Demonstrate a full data cleaning pipeline — handling missing values, dropping irrelevant features, and preparing the data for further analysis or modeling.

**Included Files**
Titanic-Dataset.csv: Raw dataset containing passenger information.

Titanic-cleaned_data.csv: Final cleaned dataset after preprocessing.

Titanic.ipynb: Google Colab showing step-by-step data cleaning, exploration, and code explanations.

Code.py: Standalone Python script for running the cleaning process and generating visualizations.

**Main Cleaning Steps**
Loaded data with Pandas

Checked for missing values and summarized null counts per column

Dropped the Cabin column due to high missingness

Imputed missing values in Age using average age by different passenger classes (using groupby)

Filled missing values for Embarked with the most common port

Exported a cleaned CSV ready for ML/modeling

**Visualizations**
Survival Distribution (Pie chart)
Age Distribution (Histogram)
Survival rates by Gender and Embarkation Port (Bar charts)
Age distribution segmented by gender
