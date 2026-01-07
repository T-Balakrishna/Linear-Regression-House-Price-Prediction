# House Price Prediction using Linear Regression

## Description

This project implements a linear regression model to predict house prices based on key property features such as area, number of bedrooms, and number of bathrooms. The focus is on building a clear, interpretable model using standard data science practices.

## Objective

To develop a predictive model that estimates housing prices accurately and supports data-driven decision-making in the real estate domain.

## Dataset

Source: Kaggle – House Prices: Advanced Regression Techniques

The dataset includes structured attributes such as lot area, year built, overall quality, number of rooms, and sale price as the target variable.

## Workflow

* Data loading and preprocessing
* Exploratory data analysis and correlation study
* Feature scaling and train-test split
* Linear regression model training
* Model evaluation using MSE and R² score
* Visualization of predicted vs actual prices

## How to Run

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Install the required dependencies:

   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn
   ```
3. Download the dataset from Kaggle and place it in the project directory.
4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
5. Open the notebook file and run all cells sequentially to train and evaluate the model.

## Results

The model achieved strong performance on test data and effectively captured linear relationships between features and house prices.

## Tech Stack

* Python (NumPy, Pandas, Scikit-learn)
* Matplotlib, Seaborn
* Jupyter Notebook
* Kaggle Dataset

## Future Enhancements

* Apply regularization techniques such as Ridge and Lasso
* Improve feature engineering for categorical variables
* Add model explainability techniques

