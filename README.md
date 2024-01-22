# Bank Statement Analysis - Cascading AI Coding Challenge

This Jupyter notebook, titled `Casca.ipynb`, is designed for the Cascading AI Coding Challenge. The notebook is comprehensive, involving installation of necessary packages, data preprocessing, analysis, and visualization of bank statements data. It concludes with the integration of GPT-4 for advanced data analysis.

## Installation

First, ensure you have the necessary packages installed:

```bash
pip install camelot-py
apt install ghostscript python3-tk
pip install ghostscript
pip install transformers torch pandas scikit-learn numpy requests
pip install fuzzywuzzy plotly
```

## Data Preprocessing

**PDF Extraction**: The script uses camelot to extract tables from PDFs. There are conditional statements to handle cases where no tables are found with the default method.
**Dataframe Creation**: Data from each bank (IDFC FIRST BANK, LLYODS BANK, US BANK, Commonwealth Bank) is converted into pandas DataFrames.
**Data Cleaning**: Includes removing unwanted columns, converting data types, handling missing values, and merging rows where necessary.

## Analysis and Visualization
**Monthly Analysis**: The notebook calculates the monthly total of credits and debits and the average monthly balance for each bank statement.
**Data Visualization**: Utilizes plotly for creating interactive bar and line charts to represent financial data visually.
**Transaction Analysis**: Sorts and analyzes the top 10 debit and credit transactions for each bank. It employs fuzzy matching to categorize transactions and generates pie charts for a visual summary.
**GPT-4 Integration**: The notebook includes a function, gpt_analysis, that sends data to the GPT-4 API for advanced analysis and insights.

## Conclusion
The notebook concludes with a comprehensive analysis of the bank statements from various banks. It emphasizes future development plans, such as creating a custom PDF processing 
solution for each bank and building an interactive interface using Streamlit.

## Usage

**Running the Code**: To execute the notebook, simply run each cell in sequence. Ensure you have an internet connection for installing packages and accessing the GPT-4 API.
**Customization**: You can customize the code for different PDF structures or extend the analysis by modifying the GPT-4 prompts.

## Requirements
Python 3
Jupyter Notebook
Internet connection for package installation and API access
Support
For any issues or inquiries, please refer to the contact information provided in the repository.

