# House Price Prediction

This project demonstrates the implementation of a Linear Regression model to predict house prices based on their square footage, number of bedrooms, and number of bathrooms. A user-friendly interface is created using `tkinter` to input house features and get the predicted price.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [User Interface](#user-interface)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project was created as part of an internship task to predict house prices using a linear regression model. The interface allows users to input the house's features and receive the predicted price instantly.

## Dataset

The dataset used in this project is from the Kaggle competition: [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data).

## Installation

To get started with this project, you need to install the required packages. 

### Prerequisites

- Python 3.7 or higher
- `pandas`
- `scikit-learn`
- `tkinter`

### Installing

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/house-price-prediction.git
    cd house-price-prediction
    ```

2. Install the required packages:
    ```bash
    pip install pandas scikit-learn
    ```

## Usage

1. Open the Jupyter notebook `HousePricePrediction.ipynb` to run and interact with the project.

2. Ensure all necessary datasets (`train.csv`, `test.csv`, `data_description.txt`) are in the same directory as the notebook.

3. Run all cells to load the data, train the model, and start the GUI.

4. Enter the house features in the provided GUI to get the predicted house price.

## Model Training

The model is trained using the following steps:

1. Load and preprocess the dataset.
2. Select relevant features: `GrLivArea`, `BedroomAbvGr`, `FullBath`, and `HalfBath`.
3. Split the data into training and testing sets.
4. Train a Linear Regression model.
5. Evaluate the model performance.

## User Interface

The user interface is built using `tkinter`. It allows users to input the house's square footage, number of bedrooms, and bathrooms, and receive the predicted price.

### Example Input and Output

- **Input Fields:**
  - Above Ground Living Area (sq ft): `2000`
  - Number of Bedrooms: `3`
  - Number of Full Bathrooms: `2`
  - Number of Half Bathrooms: `1`

- **Example Output:**
  - Predicted Price: `The predicted house price is: $250,000.00`

## Evaluation

The model's performance is evaluated using the following metrics:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

### Example Evaluation Results

```plaintext
MAE: 23325.47
MSE: 1613397647.38
RMSE: 40167.98
