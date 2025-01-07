# Enhanced Energy Management System Using Machine Learning and Deep Learning
Dissertation Project - Context-Aware Load Forecasting

## Introduction

This directory contains a Jupyter Notebook designed for load forecasting analysis using the UK DALE dataset. The notebook includes all necessary code for data preprocessing, analysis and model development. The dataset used for this project is not included in the repository. To execute the code, users must download the UK DALE dataset from the UKERC website [here](https://ukerc.rl.ac.uk/cgi-bin/dataDiscover.pl?Action=detail&dataid=7d78f943-f9fe-413b-af52-1816f9d968b0&STerm=UK-DALE&SScope=&GoAct=&AFull=4&AllFilters=&RandKey=&TotHead=TOTHEAD), and upload it to their Google Drive.

The notebook is self-contained with step-by-step instructions to guide users through the process of linking their Google Drive, loading the dataset and running the analysis.

## Project Overview

In the era of smart grids and smart homes, accurate load forecasting is essential for efficient energy management. This project develops forecasting models that address the limitations of traditional approaches by incorporating contextual information to improve prediction accuracy. The models used include GRU, LSTM, and Bidirectional LSTM, with the goal of reducing energy waste and optimizing resource allocation in residential buildings.

## Objectives

- **Develop robust forecasting models** using advanced deep learning techniques (GRU, LSTM, Bidirectional LSTM) for residential energy consumption prediction.
- **Incorporate contextual features** such as time of day, day of the week, and seasonality to improve model performance.
- **Evaluate model performance** against traditional methods like Linear Regression and Random Forest.

## Key Goals

- Predict individual appliance-level and aggregate household energy usage.
- Optimize energy consumption in residential settings by improving forecast accuracy.
- Provide insights into the temporal and contextual patterns of energy demand to assist in energy management.

## Recommended Libraries:

- numpy: Provides support for large, multi-dimensional arrays and matrices along with a collection of mathematical functions to operate on these arrays.
- pandas: Offers data structures and functions needed to efficiently manipulate structured data such as DataFrames.
- datetime: Facilitates operations on date and time objects.
- math: Provides basic mathematical functions and constants such as trigonometric and logarithmic operations.
- glob: Allows for pattern matching within the file system, useful for reading files with specific naming conventions.
- matplotlib: A fundamental plotting library for creating static, animated and interactive visualizations.
- seaborn: Builds on Matplotlib to provide a high-level interface for drawing attractive and informative statistical graphics.
- scikit-learn (sklearn): A comprehensive machine learning library that provides tools for data preprocessing, model selection, training, evaluation, and various supervised and unsupervised learning algorithms. 
  It includes utilities for tasks such as data splitting, hyperparameter tuning and performance metrics.

tensorflow/keras: A deep learning library for building and training neural networks, including models such as LSTM, GRU and convolutional neural networks.

yaml: Enables reading and writing YAML files often used for configuration settings.

## Workflow Highlights

1. **Data Preprocessing**: Includes feature scaling and sequence generation for time-series modeling, incorporating contextual features.
2. **Model Development**: Using LSTM, GRU, and Bidirectional LSTM for forecasting energy consumption based on historical data and contextual features.
3. **Evaluation**: Comparing the performance of deep learning models with traditional methods like Linear Regression and Random Forest.

## Insights

- **Contextual features** such as time of day, day of the week, and seasonal variations significantly improve the model's ability to capture complex patterns in energy consumption.
- **Deep learning models** like LSTM and GRU outperform traditional methods, achieving higher accuracy in predicting energy usage.
- Accurate load forecasting enables better demand-side management and more sustainable energy practices.

## Dataset Details

The UK Domestic Appliance-Level Electricity (DALE) dataset contains high-resolution energy consumption data from various household appliances. This dataset is instrumental in predicting power consumption and understanding appliance-level energy usage patterns.

## Troubleshooting

No Troubleshooting error found.
