# Survey Data Cleaning and Transformation (IBM Data Analytics Course Practice)

## Project Overview

This project focuses on preparing survey data for analysis using Python and Pandas. The dataset contained survey responses with multiple selections stored within individual cells, making it difficult to analyze accurately. The goal of this project was to clean, transform, and restructure the data into a format suitable for further analysis and reporting.

## Business Problem

Survey datasets often contain columns where respondents can select multiple options, resulting in several values being stored in a single cell. This structure limits effective analysis and visualization.

To address this issue, the dataset was transformed by separating multi-value responses into individual records, creating a cleaner and more analysis-ready dataset.

## Dataset

**Source:** Survey Data (`survey_data_updated 5.csv`)

The dataset contains survey responses collected from participants across various categories. Several columns required transformation to properly represent respondent selections.

## Project Tasks

- Loaded and inspected the dataset using Pandas.
- Assessed data quality and structure.
- Identified columns containing multiple responses.
- Split multi-value entries into lists.
- Applied the Pandas `explode()` function to create separate rows for each response.
- Cleaned and standardized the transformed data.
- Validated the final dataset for consistency and completeness.

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas

## Key Skills Demonstrated

- Data Cleaning
- Data Wrangling
- Data Transformation
- Exploratory Data Analysis (EDA)
- Pandas Data Manipulation
- Handling Multi-Value Survey Responses
- Data Preparation for Analysis

## Files Included

| File | Description |
|--------|-------------|
| survey_data_updated 5.csv | Original survey dataset |
| Survey_Data_Cleaning.ipynb | Jupyter Notebook containing the cleaning and transformation process |
| README.md | Project documentation |

## Outcome

The final dataset was transformed into a structured format that allows for more accurate analysis, aggregation, and visualization of survey responses. By normalizing multi-value fields into separate records, the data became more suitable for reporting and decision-making purposes.

