# Bank Marketing Data Cleaning

A DataCamp project focused on cleaning, transforming, and restructuring bank marketing campaign data using Python and Pandas. The objective was to prepare the data for storage in a PostgreSQL database.

---

## Project Objectives

Clean, standardize, and restructure bank marketing campaign data while ensuring the required data types and formats.

## Data Cleaning & Transformations

### 1. Client Data (`client.csv`)

- Replaced periods (`.`) with underscores (`_`) in job and education categories.
- Replaced unknown education values with `NaN`.
- Converted credit default and mortgage columns to boolean values.
- Retained client demographics and identification information.

### 2. Campaign Data (`campaign.csv`)

- Converted previous campaign and current campaign outcomes to boolean values.
- Created a new `year` column populated with `2022`.
- Created a new `last_contact_date` column by combining year, month, and day.
- Formatted contact dates as `YYYY-MM-DD`.
- Selected and renamed columns to match the required database structure.

### 3. Economics Data (`economics.csv`)

- Converted economic indicators to floating-point data types.
- Retained consumer price index and three-month Euribor values.

## New Columns Created

| Column | Dataset | Description |
|---|---|---|
| `year` | Campaign | New column populated with 2022 |
| `last_contact_date` | Campaign | Combined date created from year, month, and day |

## Final Output Files

| File | Contents |
|---|---|
| `client.csv` | Client demographics and financial information |
| `campaign.csv` | Campaign contacts, outcomes, and contact dates |
| `economics.csv` | Consumer price index and Euribor indicators |

## Tools & Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook
- PostgreSQL (target database)

## Project Structure

    bank-marketing-analysis/
    ├── README.md
    ├── bank_marketing_analysis.ipynb
    └── data/
        ├── bank_marketing.csv
        ├── client.csv
        ├── campaign.csv
        └── economics.csv

## Acknowledgment

Completed as part of a DataCamp project to develop practical skills in Python, data cleaning, data transformation, and database preparation.
