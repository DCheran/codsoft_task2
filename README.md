# Movie Rating Prediction with Python

## Overview

This project focuses on predicting movie ratings using machine learning techniques. The model analyzes various movie attributes such as genre, director, and cast members to estimate the rating a movie is likely to receive.

## Problem Statement

The objective is to build a regression model that can predict movie ratings based on historical movie data. Understanding the factors that influence ratings helps in analyzing audience preferences and movie performance.

## Dataset

The dataset used is the IMDb Movies India Dataset, which contains information about movies including:

* Movie Name
* Year of Release
* Duration
* Genre
* Rating
* Votes
* Director
* Actor 1
* Actor 2
* Actor 3

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

## Methodology

### 1. Data Preprocessing

* Handling missing values
* Cleaning and transforming data
* Combining actor information into a single feature

### 2. Feature Engineering

* Using Genre, Director, and Cast as predictive features
* Converting textual features into numerical representations using TF-IDF Vectorization

### 3. Model Building

* Splitting data into training and testing sets
* Training a Random Forest Regressor model

### 4. Model Evaluation

* Mean Absolute Error (MAE)
* R² Score

## Results

The model learns patterns from movie characteristics and predicts ratings based on genre, director, and cast information. Performance is evaluated using regression metrics to measure prediction accuracy.

## Future Enhancements

* Include additional features such as votes, duration, and year.
* Experiment with advanced models like XGBoost and Gradient Boosting.
* Deploy the model using Flask or Streamlit.

## Author

**Dosapati Cheran Veera Venkat**
