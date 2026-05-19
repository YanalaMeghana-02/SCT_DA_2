# SCT_DA_2
# SkillCraft Technologies Data Analyst Internship

## Task 2: Data Cleaning and Preparation

This repository contains the completed work for Task 2, focusing on cleaning and preparing the "Global Superstore" dataset using Python in Google Colab.

### Steps Performed:
* **Data Loading:** Successfully loaded the raw `superstore.csv` dataset using the standard `pandas` library.
* **Missing Value Handling:** Identified blank data blocks across the dataset and safely replaced missing values with a default placeholder (`0`) to prevent downstream analysis failures.
* **Duplicate Removal:** Scanned the dataset rows for redundant entries and successfully purged all exact duplicates.
* **Data Type Conversion:** Transformed essential date columns (like Order Date and Ship Date) into uniform `datetime` formatting to ensure smooth timeline forecasting.
* **Exporting Clean Data:** Saved and generated a fresh, error-free data sheet named `Cleaned_Dataset.csv` for submission.

### Files Uploaded:
1. `cleaning dataset.ipynb` — The completed Google Colab python notebook executing the script pipeline.
2. `Cleaned_Dataset.csv` — The finalized, clean dataset file ready for processing.
  
