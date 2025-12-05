# Movie Industry Analysis & Prediction

Academic research project developed for the Special Topics in Artificial Intelligence course.

This study investigates the key factors influencing movie success. The objective is to predict both commercial performance (Box Office) and critical reception (IMDb Score) by applying statistical analysis and Machine Learning algorithms on a dataset of over 13,000 films.

## Methodology

The project follows a structured Data Science pipeline:

**Data Cleaning & Mining:** Processing raw data, handling currency conversion, parsing complex string features (genres, actors), and treating missing values.

**Exploratory Data Analysis (EDA):** In-depth visualization using Correlation Matrices, 3D Plots, and Time Series analysis to detect seasonal trends and feature relationships.

**Preprocessing:** Application of Standard Scaling and Multi-Label Binarization for categorical data.

## Models Implemented

Various models were tested to solve Regression and Classification tasks:

- Linear Regression: Simple and Multiple regression models to estimate IMDb scores based on metascore, duration, and release year.

- Logistic Regression: Binary classification to predict Box Office success based on profit margins.

- Linear SVC: Support Vector Machine used to classify movies into rating tiers (Bad, Mid, Good).

- Deep Learning (DNN): Neural Networks built with TensorFlow/Keras for both Score Regression and Success Classification.

## Technologies

- Python 3 (Jupyter Notebook)

- Pandas & NumPy

- Scikit-Learn

- TensorFlow / Keras

- Matplotlib & Seaborn

## How to Run

Install the required libraries:

`pip install pandas numpy matplotlib seaborn scikit-learn tensorflow`

Open the Jupyter Notebook:

`jupyter notebook movie-analysis.ipynb`
