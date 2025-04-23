# Medical Insurance Charges Prediction - Linear Regression Model

## Overview

This project involves building a **Linear Regression Model** to predict medical insurance charges based on various features, including **age**, **BMI**, **smoking status**, and **number of children**. The project utilizes **Exploratory Data Analysis (EDA)**, **Feature Encoding**, and **Model Evaluation** techniques to analyze and prepare the data for model training.

## Project Description

The goal of this project is to predict medical insurance charges based on input features. This problem is relevant to health insurance companies as it helps predict the cost of health coverage based on an individual's characteristics.

The project was built using a **Jupyter Notebook** environment, and the following steps were performed:

- **Data Preprocessing**: Cleaning and transforming the data, including handling missing values.
- **Exploratory Data Analysis (EDA)**: Visualizing the data to understand relationships between features.
- **Feature Encoding**: Converting categorical data (e.g., smoking status) into numerical format for the model.
- **Model Training**: Training a linear regression model to predict the charges.
- **Model Evaluation**: Assessing model performance using metrics like Mean Squared Error (MSE) and R² score.

## Dataset

The dataset used in this project is publicly available and contains the following features:

- **Age**: Age of the policyholder.
- **BMI**: Body Mass Index of the policyholder.
- **Children**: Number of children/dependents covered by the policy.
- **Smoker**: Whether the individual is a smoker (yes/no).
- **Region**: The region in which the individual resides.
- **Charges**: The medical insurance charges for the individual (target variable).

## Requirements

To run the project, you need to install the following libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`

You can install them using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
