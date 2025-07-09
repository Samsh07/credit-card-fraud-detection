# Credit Card Fraud Detection

This project focuses on preprocessing and analyzing credit card transaction data to detect fraudulent activities. The workflow includes data cleaning, feature engineering, and exploratory data analysis to prepare the dataset for machine learning models.

## Project Structure

- `credit card fraud preprocessing-checkpoint.ipynb`: Jupyter notebook for data preprocessing and feature engineering.
- `credit card fraud visualiztion-checkpoint.ipynb`: (Empty) Notebook intended for data visualization and analysis.

## Data Preprocessing Steps

- Load transaction datasets using pandas.
- Remove unnecessary columns such as names, addresses, and transaction numbers.
- Convert date columns to datetime objects.
- Calculate customer age at the time of transaction.
- Extract time-based features (hour, day, month, day of week).
- Encode categorical variables (e.g., gender).
- Prepare the data for further analysis and modeling.

## Requirements

- Python 3.x
- pandas
- numpy
- Jupyter Notebook

## Usage

1. Place the transaction CSV files (e.g., `fraudTest.csv`, `fraudTrain.csv`) in your local directory.
2. Open `credit card fraud preprocessing-checkpoint.ipynb` in Jupyter Notebook or VS Code.
3. Run the cells to preprocess the data.
4. Use the processed data for visualization or machine learning model training.

## Notes

- Ensure the file paths in the notebook match the location of your CSV files.
- The preprocessing notebook drops sensitive columns and encodes categorical features for modeling.

## License

This project is for educational purposes.
