# Molecular Solubility Regression 🧪

This project explores multiple linear regression to predict molecular solubility using molecular descriptors such as molecular weight, number of H-bond donors, and polar surface area.

## Dataset
- [delaney-processed.csv](https://raw.githubusercontent.com/deepchem/deepchem/master/datasets/delaney-processed.csv)
- Source: DeepChem

## Features
- Multiple linear regression using scikit-learn
- Feature selection to minimize prediction error
- Visualization of actual vs predicted solubility
- Identification and inspection of top-5 outliers

## Libraries
- pandas
- numpy
- scikit-learn
- matplotlib

## Results
- Best subset of descriptors found through combination testing
- L2 error minimized through feature experimentation
- Plot showing strong correlation between actual and predicted values
- Top 5 largest prediction errors identified and visualized

## Inspiration

This project is part of a machine learning learning path, based on a YouTube tutorial series by Jan Jensen that walks through core ML concepts with practical projects.

The idea of predicting molecular solubility was inspired by one of the suggested exercises in the series:
- Perform linear regression on molecular properties to predict solubility.
- Analyze the subset of features to improve accuracy.
- Identify molecules with the largest prediction error.

While the idea was initially suggested in the tutorial, the implementation, feature selection experiments, and analysis were extended and adapted as part of a personal learning portfolio.

## Author
Created by Syamsul Rahmadi as part of a self-directed machine learning portfolio. Some implementation guidance was provided by OpenAI's ChatGPT for experimentation and code structure review.
