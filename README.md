# Optimizing Agricultural Production

## Context

Precision agriculture is increasingly important for making informed decisions about farming strategies. This project provides a dataset and tools to build a predictive model that recommends the most suitable crops to grow on a particular farm based on various parameters such as soil nutrients, temperature, humidity, pH, and rainfall.

## Dataset

The dataset `Crop_recommendation.csv` contains information about different crops and their requirements:

- **N**: Nitrogen content in the soil
- **P**: Phosphorus content in the soil
- **K**: Potassium content in the soil
- **temperature**: Temperature of the environment
- **humidity**: Humidity of the environment
- **ph**: pH level of the soil
- **rainfall**: Rainfall in the area
- **label**: Crop name

## Project Overview

This project involves the following steps:

1. **Data Exploration**: Understanding the dataset, checking for missing values, and summarizing crop statistics.
2. **Interactive Analysis**: Using interactive widgets to explore crop requirements and compare them with average conditions.
3. **Clustering**: Applying K-Means clustering to group similar crops based on their requirements.
4. **Predictive Modeling**: Building a logistic regression model to predict the most suitable crop based on input parameters.
5. **Model Evaluation**: Assessing the model's performance using confusion matrices.
6. **Real-Time Prediction**: Making real-time predictions for new data.

## Installation

Install the necessary Python libraries:

```bash
pip install pandas numpy matplotlib seaborn ipywidgets scikit-learn
