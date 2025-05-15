# Financial Report PDF Extraction & Cleaning

## Table of Contents

1. [Description](#description)  
2. [Objective](#objective)  
3. [Tools & Libraries](#tools--libraries)  
4. [Steps](#steps)  
5. [Notes](#notes)  

---

## Description

This project extracts and cleans financial data from a quarterly PDF report published by Bank BJB. It processes raw PDF data into a structured format for further financial analysis.

---

## Objective

- Extract account names and amounts from PDF.  
- Clean and standardize amounts.  
- Set specific accounts' amounts to zero.  
- Group accounts by financial categories.  
- Adjust amount signs based on account type.  
- Export cleaned data to Excel.

---

## Tools & Libraries

- Python 3.x  
- pandas  
- Custom PDF processing functions  
- openpyxl (optional)

---

## Steps

1. Set PDF URL.  
2. Extract raw data from PDF.  
3. Clean and convert amount data.  
4. Reset amounts for specific accounts.  
5. Group accounts into categories (Assets, Liabilities, Equity, Profit & Loss).  
6. Modify amounts to reflect correct sign conventions.  
7. Export final dataframe to Excel.

---

## Notes

- Ensure `process_pdf_from_url` and `extract_account_amount` functions are available.  
- Grouping and data cleaning assume a consistent PDF layout.
