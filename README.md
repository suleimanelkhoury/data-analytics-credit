# Data Analytics Credit Prediction

## Project Overview

This project focuses on predicting the balance of various bank users based on their attributes. The dataset comprises user attributes and their corresponding balances. The objective is to build a predictive model that can accurately estimate the balance for each user. The model's performance is evaluated using Mean Absolute Error (MAE).

## Files

- **notebook.ipynb**: The Jupyter Notebook containing the entire process of data analysis, preprocessing, model development, and evaluation.
- **credit_train.csv**: The training dataset containing user attributes and the target balance.
- **credit_test.csv**: The test dataset for which predictions need to be made. It contains user attributes without the target balance.
- **credit_test_sample.csv**: A sample submission file showing the format in which the predictions should be submitted.
- **requirements.txt**: A file listing all the Python packages required to run the notebook.

## Requirements

To run the Jupyter Notebook, you'll need to install the necessary Python packages listed in `requirements.txt`. You can install them using pip:

```bash
pip install -r requirements.txt
```

## How to Run the Project

1. **Clone the repository**:
    ```bash
    git clone https://github.com/suleimanelkhoury/data-analytics-credit.git
    cd data-analytics-credit
    ```

2. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter Notebook**:
    Open the `notebook.ipynb` file in Jupyter Notebook or Jupyter Lab and run the cells step by step to:
    - Load and explore the data.
    - Preprocess the data (handling missing values, feature encoding, etc.).
    - Train various machine learning models.
    - Evaluate the models using MAE.
    - Make predictions on the test set.

4. **Generate Submission**:
    - After running the notebook, predictions for the test set will be saved in the format of `credit_test_sample.csv`.
    - Modify and save the results as a `.csv` file to submit to the Kaggle competition.

## Data

The data is provided in CSV format and consists of user attributes such as age, income, and others. The training dataset (`credit_train.csv`) includes the balance, which is the target variable.

## Model Evaluation

The performance of the models is evaluated using the Mean Absolute Error (MAE). MAE measures the average magnitude of the errors in a set of predictions, without considering their direction.
