# Health-tracker-data-analysis

This project analyzes data from a wearable health tracker device that collects data for its users to monitor their physical activity. The main objective is to estimate the model bias and variance and select a family of models for further model development.

### Project Highlights

**Aggregate Sample Creation**: Created an aggregate sample from the user event data to perform data analysis and modeling.

**MLFlow Experiment Design**: Designed an MLFlow experiment to estimate model bias and variance.

**Exploratory Data Analysis**: Performed EDA to understand the dataset better and select the important features from a combination of features.

**Model Development**: Developed DecisionTreeClassifier and Linear classification model - LogisticRegression on the sample data using cross-validation.

**Feature Visualization**: Used TSNE to visualize multi-dimensional features into two-dimensional vector space.

### Tools and Technologies Used

PySpark
Databricks
MLFlow
DecisionTreeClassifier
LogisticRegression
TSNE
Pandas
NumPy
Matplotlib

### Project Structure

includes/configuration.ipynb/: This directory contains configuration files for the project.
includes/utilities.ipynb/: This directory contains useful helper functions used in the actual development notebook.
includes/preprocessing.ipynb: This notebook file contains the data preprocessing steps.
includes/health-tracker-analysis.ipynb: This notebook file contains the main development steps including data analysis, modeling, and feature visualization.
README.md: This file contains the project description and structure.

### Usage

To use this project, you will need to have access to Databricks and PySpark.

1) Clone this repository to your local machine using git clone.
2) Upload the notebook files to your Databricks workspace.
3) Open health-tracker-analysis.ipynb and run the cells to perform data analysis, modeling, and feature visualization.

### Conclusion

This project provides insights into the bias and variance tradeoff for wearable health tracker data. It shows how to use cross-validation to select important features and fit different classification models to the sample data. The feature visualization using TSNE also helps to understand the multi-dimensional features in a two-dimensional space. The code and notebooks in this repository can be used as a starting point for similar projects.
