
Dataset

A tabular housing dataset (e.g., Kaggle "House Prices" dataset) containing property records with features such as square footage, number of bedrooms and bathrooms, location, year built, and lot size, along with the actual sale price for each house.

Format: CSV
Source: Open-source platform (Kaggle / UCI / OpenML)
Machine Learning Problem Definition

Type of problem: Regression

This is a regression problem because the goal is to predict a continuous numeric value (the house price), not a category or a cluster.

Target variable: House sale price (continuous numerical value). This is a supervised learning problem since the true price for each house is provided in the dataset.

What the model learns: The model learns the relationship between a house's features (size, number of rooms, location, condition, age, etc.) and its final sale price, so it can predict the price of a new, unseen house based on its features.

Problem Statement

Given a set of features describing a house — such as its size, number of bedrooms and bathrooms, location, and age — the goal is to build a regression model that predicts the house's sale price. This helps buyers, sellers, and real estate agents estimate a fair market value based on measurable property characteristics.

Methodology

The project follows this workflow:

Dataset Selection
Data Loading
Data Preprocessing
Train/Test Split
Model Training
Model Evaluation
Results
