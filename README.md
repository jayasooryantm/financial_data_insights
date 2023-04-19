# Credit Card Data Analysis for Customer Approval

This project aims to analyze credit card application data to understand which customers would benefit from a credit card and which would not, based on the previous customer data.

## Description of data columns

The dataset provided by the client contains the following columns:

- `card`: Dummy variable, 1 if application for credit card accepted, 0 if not
- `reports`: Number of major derogatory reports
- `age`: Age in years plus twelfths of a year
- `income`: Yearly income
- `share`: Ratio of monthly credit card expenditure to yearly income
- `expenditure`: Average monthly credit card expenditure
- `owner`: 1 if owns their home, 0 if rent
- `selfempl`: 1 if self-employed, 0 if not
- `dependents`: 1 + number of dependents
- `months`: Months living at current address
- `majorcards`: Number of major credit cards held
- `active`: Number of active credit accounts

## Installation

To install and set up the project, follow these steps:

1. Clone the repository.
2. Install the required dependencies or libraries.
3. Download the dataset provided by the client.
4. Load the dataset into a database or data warehouse, such as Google BigQuery.
5. Connect to the database or data warehouse using the appropriate credentials.

## Usage

To use the project, follow these steps:

1. Once you have installed the project, open it in your preferred IDE.
2. Run the SQL queries located in the "Process Phase" section of the README file to clean and process the data.
3. Use the processed data to extract insights about the credit card holders, such as who are the customers maintaining a credit card account without failing the repayment, and who are the customers failing to repay the amount.

## Contributing

Contributions to this project are welcome. To get involved, please follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Test your changes.
5. Submit a pull request with a detailed description of your changes.
