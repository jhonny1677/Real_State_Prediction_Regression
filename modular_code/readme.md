This repository contains modular code for real estate prediction regression, a task that involves predicting the prices or values of real estate properties. The code is designed to facilitate the regression analysis of real estate data using various features and data points.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Methods](#methods)
- [Contributing](#contributing)
- [License](#license)

## Installation

To use the Real Estate Prediction Regression code, follow these installation steps:

1. Clone the repository to your local machine by executing the following command:

    ```
    git clone https://github.com/jhonny1677/Real_State_Prediction_Regression.git
    ```

2. Ensure you have Python 3.x and pip installed on your system.

3. Install the required dependencies by running the following command:

    ```
    pip install -r requirements.txt
    ```

4. Download or prepare your dataset to be used for real estate prediction regression. Make sure the dataset is in a suitable format and structure for training and evaluation.

## Usage

Once you have the repository and dependencies set up, you can use the modular code for real estate prediction regression as follows:

1. Prepare your dataset for training and evaluation. The dataset should include features (X) and the target variable (y), where X represents the input features and y represents the real estate property prices or values.

2. Use the provided modules and code files to perform tasks such as data preprocessing, feature engineering, model training, evaluation, and prediction. The modular structure allows you to customize and combine different components based on your requirements.

3. Start with the `EDA.py` module to preprocess your dataset, handle missing values, perform feature scaling, and encode categorical variables.

4. Use the `feature_engineering.py` module to create additional features or transform existing features to enhance the predictive power of your model.

5. Utilize the `ML Model building.py` module to train and optimize your regression model using various algorithms such as linear regression,rigde regression,lasso regression, decision trees, random forests, or gradient boosting.

6. Evaluate the performance of your trained models using the `model_evaluation.py` module. Calculate metrics such as mean squared error (MSE), root mean squared error (RMSE), mean absolute error (MAE), or R-squared to assess the model's effectiveness.

7. Finally, use the trained model to make predictions on new real estate property data using using the using the `engine.py` module.

8. Enter 1 to train the model or Enter 2 to run the FastAPI app.py file to run the web application


Feel free to modify the provided code, add your own algorithms, or customize the workflow to suit your specific real estate prediction regression needs.

## Data

The Real Estate Prediction Regression code expects a prepared dataset in a suitable format. Make sure your dataset includes features (X) and the target variable (y) and is appropriately preprocessed before using the code. You can replace the example dataset provided with your own data or update the code accordingly.

## Methods

The modular code for real estate prediction regression includes various methods and techniques, such as:

- Data preprocessing: Handling missing values, feature scaling, and encoding categorical variables.
- Feature engineering: Creating new features or transforming existing features to improve model performance.
- Model training: Utilizing algorithms like linear regression, decision trees, random forests, or gradient boosting for regression analysis.
- Model evaluation: Assessing the performance of trained models using metrics such as mean squared error (MSE), root mean squared error (RMSE), mean absolute error (MAE), or R-squared.
- Model prediction: Using the trained model to make predictions on new real estate property data.

Each module and code file provides detailed comments
