## README: Data Analysis Program

### Overview
This program is designed to analyze sales data from a CSV file and answer key questions such as which month and city have the highest sales. The program uses Python and the `pandas` library to perform data manipulation and analysis.

### Features
- **Data Loading**: Reads sales data from a CSV file.
- **Data Cleaning**: Ensures date columns are in the correct datetime format.
- **Data Transformation**: Extracts month and city information from the data.
- **Analysis**: Identifies the month and city with the highest sales.
- **Output**: Displays the results of the analysis in a readable format.

### Requirements
- Python 3.x
- pandas library

### Installation
1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/data-analysis-program.git
    ```
2. **Navigate to the project directory**:
    ```sh
    cd data-analysis-program
    ```
3. **Install the required Python packages**:
    ```sh
    import pandas as pd
    import os
    import seaborn as sns
    import matplotlib.pyplot as plt
    ```
### Usage
1. **Place your CSV file in the project directory** and ensure it is named `Sales Data.csv`.

2. **Run the analysis script**:
    ```sh
    python analyze_sales.py
    ```

3. **Expected CSV File Structure**:
    The CSV file should have the following columns:
    - `id`: Unique identifier for each sale.
    - `sales_amount`: The amount of sales.
    - `date`: The date of the sale (YYYY-MM-DD format).
    - `city`: The city where the sale occurred.

### Analysis Details
- **Month with the Highest Sales**:
    The program calculates the total sales for each month and identifies the month with the highest total sales.
- **City with the Highest Sales**:
    The program calculates the total sales for each city and identifies the city with the highest total sales.

### Example Output
After running the script, you will see an output similar to:
```
Month with the highest sales: 2023-03 with total sales of 600.0
City with the highest sales: Philadelphia with total sales of 350.0
```
This README file provides all the necessary information to understand, install, and use the data analysis program effectively. If you have any further questions or need assistance, please contact the project maintainer.
