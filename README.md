# GDP Data Cleaning using Pandas

## Project Overview
This project demonstrates how Python can be used to extract, clean, and transform real-world data. GDP data is scraped from Wikipedia and processed using Pandas.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

## Project Workflow
1. Extract GDP table from website using `pandas.read_html()`
2. Clean the dataset and remove irrelevant rows
3. Handle missing values and convert data types
4. Convert GDP values from Million USD to Billion USD
5. Perform basic analysis and visualization
6. Export cleaned dataset to CSV

## Note
Some countries had missing GDP estimates in the source dataset. These values were preserved as NaN to maintain data integrity.
