# Bank Marketing Data Cleaning

A DataCamp project focused on cleaning and transforming bank marketing campaign data using Python and Pandas. The objective was to prepare the data for storage in a PostgreSQL database.

---

## Project Objectives

- Clean and standardize client information.
- Convert columns to the required data types.
- Handle missing and unknown values.
- Create a last_contact_date column using day, month, and year (2022).
- Separate the cleaned data into three CSV files.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook
- PostgreSQL

## Project Structure

bank-marketing-analysis/
├── README.md
├── bank_marketing_analysis.ipynb
└── data/
    ├── bank_marketing.csv
    ├── client.csv
    ├── campaign.csv
    └── economics.csv

## Output Files

| File | Description |
|---|---|
| client.csv | Client demographics and financial information |
| campaign.csv | Campaign contacts, outcomes, and contact dates |
| economics.csv | Consumer price index and Euribor indicators |

## Acknowledgment

Completed as part of a DataCamp project to develop practical skills in Python, data cleaning, and data preparation for database integration.
