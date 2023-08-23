# Loan Default Analysis and Classifier

This document outlines the steps to run the Python notebook for analyzing loan default data and building a classifier. The notebook utilizes various data wrangling, visualization, and analysis techniques.

## Source of the Dataset
The dataset can be download from [Kaggle](https://www.kaggle.com/datasets/ethon0426/lending-club-20072020q1)

## Summary

1. **Environment Setup**: Install required libraries and create a virtual environment.
2. **Data Preparation**: Mount Google Drive, unzip the dataset, and load it into a Dask-cuDF DataFrame.
3. **Data Wrangling**: Check for missing values, drop columns with high missing percentages, and fill missing values.
4. **Descriptive Analytics**: Explore data using histograms, box plots, scatter plots, and kernel density estimation (KDE).
5. **Diagnostic Analytics**: Analyze correlations among numeric columns using a heatmap and visualize word frequencies with a WordCloud.

## Summary of the Notebook

The notebook performs the following tasks:

- Installs necessary libraries and sets up a virtual environment.
- Loads a loan dataset and preprocesses it using Dask-cuDF.
- Conducts data wrangling, including handling missing values and feature selection.
- Analyzes data distribution and relationships through descriptive and diagnostic visualizations.
- Utilizes a Random Forest Classifier to predict loan default based on selected features.
- Presents summary statistics, correlation matrices, and visualizations for insights.

## Usage

It is recommended that you run the Notebook file on [Google Colab](https://colab.research.google.com/).
