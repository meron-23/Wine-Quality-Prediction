# Wine Quality Prediction

## Overview

This project implements a linear regression model to predict the quality of wine based on various features. The model is built using data from the Wine Quality dataset and is developed in Jupyter Notebooks.

## Table of Contents

1. [Introduction](#introduction)
2. [Data](#data)
3. [Model Development](#model-development)
4. [Results](#results)
5. [Usage](#usage)
6. [Requirements](#requirements)
7. [License](#license)

## Introduction

The goal of this project is to predict the quality of wine based on its chemical properties using linear regression. The dataset used contains various features of wine, such as acidity, sugar, pH, and others, which are used to build and evaluate the model.

## Data

The dataset used in this project is the Wine Quality dataset, which is available from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality). 

### Features

- `fixed acidity`
- `volatile acidity`
- `citric acid`
- `residual sugar`
- `chlorides`
- `free sulfur dioxide`
- `total sulfur dioxide`
- `density`
- `pH`
- `sulphates`
- `alcohol`

### Target

- `quality`: A score between 0 and 10, indicating the quality of the wine.

## Model Development

The following steps were followed to develop the linear regression model:

1. **Data Preprocessing**: Cleaning and preparing the data for modeling.
2. **Feature Selection**: Identifying the most significant features affecting wine quality.
3. **Model Training**: Using linear regression to build the predictive model.
4. **Evaluation**: Assessing the model's performance using appropriate metrics such as Mean Squared Error (MSE) and R-squared score.

The notebook files included in this repository detail each of these steps.

## Results

The results of the model are summarized in the notebooks. Key metrics include:

- **Mean Squared Error (MSE)**
- **R-squared Score**

These metrics provide insights into the performance of the linear regression model in predicting wine quality.

## Usage

To run the analysis and train the model, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/wine-quality-prediction.git
2. **Navigate to the Project Directory**

   ```bash
   cd wine-quality-prediction
   Install Dependencies
   
3. **Create a virtual environment and install the necessary packages:**

   ```bash
   pip install -r requirements.txt
   Run the Notebooks

4. **Open the Jupyter Notebooks:**

   ```bash
   jupyter notebook
Navigate to the notebook files and execute the cells to replicate the analysis.

## Requirements
The project requires the following Python packages:

- **numpy**
- **pandas**
- **matplotlib**
- **scikit-learn**
- **jupyter**

**These can be installed using pip:**
   ```bash
   pip install numpy pandas matplotlib scikit-learn jupyter

## License
This project is licensed under the MIT License. See the LICENSE file for details.

