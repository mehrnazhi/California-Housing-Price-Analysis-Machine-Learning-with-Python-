California Housing Price Analysis
Project Overview

This project analyzes housing prices in California using Python and Jupyter Notebook.
The dataset contains features such as longitude, latitude, median income, population, households, and proximity to the ocean.
The goal is to explore, clean, transform, and prepare the dataset for predictive modeling.

Main Steps

Data Exploration:

Checked data types and column distributions.

Examined correlations and relationships using scatter matrix plots.

Data Splitting:

Divided the dataset into training and test sets for unbiased model evaluation.

Data Cleaning:

Handled missing values using SimpleImputer (filled with mean).

Feature Engineering:

Created new features such as population per household.

Feature Scaling:

Standardized numeric features with StandardScaler.

Categorical Encoding:

Converted ocean_proximity into numerical format using OneHotEncoder.

Requirements

Python 3.x

pandas

numpy

scikit-learn

matplotlib / seaborn (optional for visualization)

How to Run

Clone the repository:

git@github.com:mehrnazhi/California-Housing-Price-Analysis-Machine-Learning-with-Python-.git


Open the Jupyter Notebook and run the cells step by step.

Results

Cleaned and transformed dataset ready for machine learning.

Visualizations of correlations and feature distributions.

Optional

You can extend this project by building regression models to predict housing prices.
