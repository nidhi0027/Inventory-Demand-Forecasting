# Inventory Demand Forecasting

## Overview

This project focuses on forecasting product demand across multiple stores using historical sales data. Accurate demand forecasting helps businesses optimize inventory levels, reduce stockouts, and improve supply chain planning.

## Objective

Build a machine learning model that predicts future product demand based on historical sales patterns, store information, and time-based features.

## Dataset Features

* Date
* Store ID
* Item ID
* Historical Sales

## Feature Engineering

The following features were created to improve forecasting performance:

* Year
* Month
* Day
* Weekend Indicator
* Holiday Indicator
* Cyclical Month Features (Sine & Cosine Transformation)

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn

## Workflow

1. Data Cleaning & Preprocessing
2. Feature Engineering
3. Time-Based Train/Test Split
4. Feature Scaling
5. Model Training
6. Model Evaluation
7. Demand Forecasting

## Results

The model learns demand patterns from historical sales data and generates forecasts that can support inventory planning and business decision-making.

## Project Structure

```text
Inventory-Demand-Forecasting/
├── Inventory_Demand_Forecasting.ipynb
├── README.md
├── environment.yml
└── train.csv
```

## Installation

Create the Conda environment using:

```bash
conda env create -f environment.yml
conda activate <environment_name>
```

