# Data-cleaning-sales

- `cleaned_customer_orders.csv`: Final cleaned dataset with high-value transactions


# Data-cleaning-sales

This project uses Python and pandas in Google Colab to clean and filter customer order data. It includes a full notebook showing the cleaning process, error handling, and final export of high-value transactions over $100.

* `cleaned_customer_orders.csv` : Final cleaned dataset with high-value transactions

- ## Features
- Removed missing values and duplicate rows
- Renamed columns for clarity
- Converted revenue values to numeric format
- Filtered high-value transactions over $100
- Debugged column mismatch error (`KeyError: 'Revenue'`) and corrected column mapping

## Files
- `Sales_data_cleaning.ipynb`: Colab notebook with full cleaning process
- `customer_orders.csv`: Original dataset
- `cleaned_customer_orders.csv`: Final cleaned output

## Tools Used
- Python
- pandas
- Google Colab
