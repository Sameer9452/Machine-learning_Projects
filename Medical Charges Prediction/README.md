# Medical Charges Prediction using Linear Regression and SGD

This repository contains a project that predicts medical charges using Linear Regression and Stochastic Gradient Descent (SGD) Regression. The dataset includes various features such as age, BMI, number of children, smoking status, sex, and region.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Feature Engineering](#feature-engineering)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The goal of this project is to build a predictive model that estimates medical charges based on demographic and health-related features. We employ both standard Linear Regression and SGDRegressor from scikit-learn to build and evaluate our models.

## Dataset

The dataset used in this project contains the following columns:
- `age`: Age of the individual
- `sex`: Gender of the individual
- `bmi`: Body Mass Index of the individual
- `children`: Number of children/dependents
- `smoker`: Smoking status of the individual
- `region`: Geographical region where the individual resides
- `charges`: Medical charges billed by healthcare providers

## Feature Engineering

### Scaling Numeric Features
To ensure fair weight comparison and model performance, we scale the numeric features (age, BMI, children) using `StandardScaler` from scikit-learn.

### Encoding Categorical Features
Categorical features (sex, smoker, region) are encoded into numeric values to be used in the regression models.

## Modeling

### Linear Regression
We first build a Linear Regression model to understand the relationships between the features and the target variable (charges).

### SGD Regressor
To improve the model's efficiency and handle larger datasets, we implement an SGD Regressor with the following parameters:
- `max_iter=1000`
- `tol=1e-3`

## Evaluation

We evaluate our models using Root Mean Square Error (RMSE), which provides insight into the model's prediction accuracy.

### Results
- **Linear Regression RMSE Loss:** 6041.68
- **SGD Regressor RMSE Loss:** 6042.55

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/medical-charges-prediction.git
   cd medical-charges-prediction
   ```

2. Create a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate   # On Windows, use `env\Scripts\activate`
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Prepare your dataset by ensuring it has the required columns.
2. Run the script to train the model and make predictions:
   ```bash
   python main.py
   ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or suggestions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to explore the repository and use the provided code to understand the modeling process better. Happy coding!
