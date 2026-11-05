# SWYNEX-Data-Science-Internship: Task 1 - Data Preparation

## Overview
This repository contains the code and deliverables for **Task 1: Data Preparation** as part of the SWYNEX Data Science Internship. The objective of this task is to select a public dataset, handle missing values, correct data types, and document all data cleaning assumptions.

## Dataset Information
* **Dataset Name:** TCGA-LUAD (The Cancer Genome Atlas - Lung Adenocarcinoma) Clinical Dataset
* **Source:** National Cancer Institute (NCI) GDC Data Portal (`clinical.tsv`)
* **Description:** Contains comprehensive clinical and demographic metadata for lung adenocarcinoma patients, serving as a standard benchmark for biomedical data science workflows.

## Files Included in Repository
* `TCGA-LUAD_Data_cleaning.ipynb`: The complete Jupyter notebook showing data loading, inspection, handling of missing values, and type conversions.
* `cleaned_clinical_tcga_luad.csv`: The final sanitized and processed dataset ready for downstream exploratory data analysis (EDA) and modeling.

## Data Cleaning & Preparation Steps
1. **Data Ingestion:** Loaded the raw `clinical.tsv` file into a Pandas DataFrame.
2. **Missing Value Management:** Identified custom missing value markers (such as `"--"`) across columns and standardized them to Pandas `NaN` values using `numpy.nan`.
3. **Filtering & Standardization:** Filtered out unneeded empty rows/columns and ensured proper structure for downstream analysis.
4. **Export:** Saved the cleaned output into a structured CSV format (`cleaned_clinical_tcga_luad.csv`).

## Author
* **Name:** Harshitha Ghantasala
* **Student ID:** 251FA14022
* **Intern ID:** SWX-2026-003368
