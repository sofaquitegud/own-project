# House Sales Prediction

This project is a practical exam for RealAgents, a real estate company that focuses on optimizing house sale prices.

## Project Overview

RealAgents wants to predict house sale prices to reduce the time to sale. This project includes tasks to clean and analyze house data and build models to predict house prices.

## Tasks

1. **Identify and Replace Missing Values in `city`**: Count missing values in `city` and replace with `"Unknown"`.
2. **Data Cleaning**: Prepare the dataset by handling missing values and formatting columns.
3. **Analyze Sale Price by Number of Bedrooms**: Calculate the average sale price and variance based on the number of bedrooms.
4. **Baseline Model (Linear Regression)**: Fit a linear regression model to predict house sale prices.
5. **Comparison Model (Random Forest)**: Fit a random forest model for comparison with the baseline.

## Usage

1. Clone the repository.
2. Ensure `pandas` and `scikit-learn` are installed (`pip install pandas scikit-learn`).
3. Run the following command to clone the repository:

   ```bash
   git clone https://github.com/sofaquitegud/own-project.git
   ```
4. Open the `house-sales-prediction.ipynb` notebook in Jupyter Notebook or JupyterLab.
5. Run each cell sequentially to execute the tasks.

## Files

- `House_Sales_Prediction.ipynb`: The main notebook file containing all tasks and models.
- `house_sales.csv`: Dataset of previous house sales.
- `train.csv`: Training dataset for models.
- `validation.csv`: Validation dataset for models.
