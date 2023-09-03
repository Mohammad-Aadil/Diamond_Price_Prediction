# Diamond Price Prediction

## Overview
Welcome to the Diamond Price Prediction project! This project leverages machine learning to predict diamond prices based on various attributes, including carat, cut, color, clarity, depth, table, and dimensions (x, y, z). It also offers a user-friendly web application for quick price predictions.

## Project Structure
Here's an overview of the project structure:

- data/
    -gemstone.csv
-logs/
    -<log_files>
- src/
    - components/
- data_ingestion.py
- data_transformation.py
- model_trainer.py
- exception.py
- logger.py
- pipelines/
    - prediction_pipeline.py
- utils.py
- templates/
    - form.html
    - index.html
- app.py
- training_pipeline.py
- requirements.txt
- setup.py

## Setup and Installation
1. Install the required dependencies by running the following command:
pip install -r requirements.txt


## Data
The project uses the `gemstone.csv` dataset located in the `data/` directory. This dataset contains valuable information about diamonds, such as carat weight, cut quality, color, clarity, depth percentage, table size, dimensions (x, y, z), and price.

## Exploratory Data Analysis (EDA)
An in-depth Exploratory Data Analysis (EDA) has been performed to gain insights into the dataset, which comprises 193,573 rows and 11 columns. These columns encompass both numerical and categorical features, including custom rankings for ordinal variables.

## Model Training
The project employs various machine learning models for training, including Linear Regression, Lasso, Ridge, and ElasticNet. These models are evaluated using essential metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R2) score to ensure their predictive performance.

## Prediction Pipeline
The `prediction_pipeline.py` file is responsible for the prediction pipeline. It employs a pre-trained model and preprocessor to transform input data and deliver precise diamond price predictions.

## Exception Handling
For robust error handling, the project incorporates the `exception.py` module, which captures and logs exceptions that may arise during execution.

## Logging
Logging is an integral part of this project, facilitated by the `logger.py` module. It logs messages and errors, and the log files are conveniently stored in the `logs/` directory.

## Usage
1. Launch the Flask application with the following command:

python app.py

2. Access the web application via your web browser at `http://localhost:5000/`.

## Dependencies
The project relies on the following Python libraries and packages:
- pandas
- numpy
- seaborn
- flask
- scikit-learn

You can easily install these dependencies using the command mentioned in the `requirements.txt` file.

## Contributors
- Mohammad Aadil

