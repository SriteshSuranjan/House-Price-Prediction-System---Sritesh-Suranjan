# House-Price-Prediction-System---Sritesh-Suranjan

# House Price Prediction

## Overview

This project aims to predict house prices using machine learning techniques. It involves loading and exploring a housing dataset, preprocessing the data, visualizing key features, and building predictive models. The implementation utilizes popular Python libraries such as NumPy, Matplotlib, Pandas, Seaborn, and scikit-learn.

## Table of Contents

- [Data Loading and Exploration](#data-loading-and-exploration)
- [Data Preprocessing](#data-preprocessing)
- [Train-Test Split](#train-test-split)
- [Data Visualization](#data-visualization)
- [Feature Engineering](#feature-engineering)
- [Feature Creation](#feature-creation)
- [Model Building](#model-building)
- [Model Evaluation](#model-evaluation)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Data Loading and Exploration

The initial step involves loading the housing dataset and exploring its basic characteristics, such as data types, missing values, and a summary of statistics.

## Data Preprocessing

Preprocessing steps include handling missing values and splitting the dataset into feature variables (x) and the target variable (y).

## Train-Test Split

The dataset is divided into training and testing sets to facilitate model evaluation.

## Data Visualization

Visualization techniques, including histograms and heatmaps, are employed to better understand the distribution and relationships between different features in the dataset.

## Feature Engineering

Logarithmic transformations and one-hot encoding are applied to certain features to address skewness and convert categorical variables into numerical columns.

## Feature Creation

Additional features, such as 'bedroom_ratio' and 'household_rooms,' are created to enhance the model's predictive capabilities.

## Model Building

Two regression models, Linear Regression and K-Nearest Neighbors (KNN) Regression, are implemented using scikit-learn.

## Model Evaluation

The accuracy of each model is evaluated using the testing dataset, providing insights into their predictive performance.

## Dependencies

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn

## Usage

1. Install the required dependencies: `pip install -r requirements.txt`
2. Run the Jupyter notebook or Python script.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.
