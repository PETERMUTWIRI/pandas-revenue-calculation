### Pandas Revenue Calculation

This is a simple Python script that calculates the revenue for a business using Pandas, a popular data analysis library.
How to Use

    Install Python 3.x on your machine, if you don't already have it installed.
    Install the required dependencies using pip install -r requirements.txt.
    Create a CSV file with the following columns: product, price, and quantity. Each row represents a sale.
    Save the CSV file in the same directory as the script.
    Run python revenue_calculation.py.
    Follow the prompts to enter the name of the CSV file and the name of the column that contains the product names.
    The script will calculate the revenue for each product and display the results in the console.

### How it Works

The script uses Pandas to read the CSV file and create a DataFrame. It then groups the rows by the product column and calculates the sum of the price column multiplied by the quantity column for each group. The result is a new DataFrame with two columns: product and revenue. The script then sorts the DataFrame in descending order by revenue and displays the results in the console.
### Dependencies

This script requires Python 3.x and the following dependencies:

    Pandas: A data analysis library for Python.
    NumPy: A library for the Python programming language, adding support for large, multi-dimensional arrays and matrices.
    Matplotlib: A plotting library for the Python programming language and its numerical mathematics extension NumPy.
