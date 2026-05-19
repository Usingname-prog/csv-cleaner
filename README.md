# CSV Report Automation

Python automation that processes the messy csv file, generates summary reports, and makes plots.

## Purpose of the Project

This project aims to automate the process of common data cleaning.

This script does the following:

- reads in messy csv file
- cleans column names
- drops blank rows
- drops duplicates rows
- detects numeric columns
- detects datetime columns
- generates summary report
- makes charts

This Python project showcases knowledge about data manipulation and reporting and demonstrates understanding of data cleaning principles which are relevant for entry level data and operations positions.

## Technologies Used

- Python
- pandas
- matplotlib

## Structure of the Project

```
csv-cleaner/
│
├── main.py
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│   └── sample_orders.csv
│
└── example_output/
    ├── cleaned_data.csv
    ├── report.csv
    └── charts/
