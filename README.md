# Employee Attrition Analysis



This repository contains Python code for analyzing employee attrition using various data visualization techniques and a machine learning model.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Usage](#usage)
- [Data](#data)
- [Analysis](#analysis)
- [Machine Learning](#machine-learning)
- [Results](#results)
- [License](#license)

## Introduction

The goal of this project is to analyze factors contributing to employee attrition and build a machine learning model to predict attrition. The code includes data visualization using `matplotlib`, `seaborn`, and `plotly`, as well as a machine learning model using `scikit-learn` and `imbalanced-learn`.

## Requirements

To run the code, you need to have the following Python packages installed:

- `numpy`
- `pandas`
- `seaborn`
- `matplotlib`
- `plotly`
- `scikit-learn`
- `imbalanced-learn`

You can install these packages using the following command:

` pip install numpy pandas seaborn matplotlib plotly scikit-learn imbalanced-learn `

Usage
# Clone the repository:

git clone `https://github.com/your-username/employee-attrition-analysis.git`

Navigate to the project directory:

`cd employee-attrition-analysis`

Run the Jupyter notebook or Python script:
If using Jupyter:

`jupyter notebook`
If using a Python script:

`python your_script.py`
# Review the Results:

Once the script or notebook is executed, it will print the accuracy score and classification report for the Random Forest model. Additionally, explore the generated visualizations in the notebook or check the output files, if any.

# Data
The dataset used for this analysis is stored in the `EmployeeAttrition.csv` file. The dataset includes various features related to employees and their attrition status.

# Analysis
The code includes data visualization using seaborn, matplotlib, and plotly. It explores relationships between different features and visualizes the dataset's characteristics.

# Additional Data Analysis
In addition to the machine learning model, the code includes detailed data analysis through visualizations. Some of the key visualizations include:

Age vs Total Working Years
Age vs Daily Rate
Years in Current Role vs Age
Daily Rate vs Distance from Home
Daily Rate vs Job Satisfaction
Years at Company vs Daily Rate
Years at Company vs Distance
Relationship Satisfaction vs Years with Manager
Work-Life Balance vs Satisfaction
These visualizations provide insights into the relationships between various attributes in the dataset.

# Machine Learning
The machine learning part of the code involves building a random forest classifier using scikit-learn. The model is trained on the provided dataset to predict employee attrition.

# Results
The results of the machine learning model, including accuracy scores and classification reports, are printed in the console. Additionally, feature importance is visualized using a scatter plot.

