# 📊 Data_Viz

## Overview

Data_Viz is a preprocessing and structuring pipeline designed to provide a clear, reproducible foundation for the visualization of WAVE data in Power BI.

The repository focuses on transforming raw and intermediate datasets into analysis-ready formats, ensuring consistency, traceability, and compatibility with downstream visualization workflows.

## 🎯 Objectives

* Standardize WAVE datasets prior to visualization
* Ensure data quality and consistency across sources
* Facilitate reproducible data transformations
* Prepare structured outputs optimized for Power BI dashboards

## 🗂️ Repository Structure

```bash 
Data_Viz/
├── data/
│   ├── raw/              # Original datasets (unaltered)
│   ├── processed/        # Cleaned and transformed datasets
│   └── external/         # Supplementary or reference data
├── scripts/              # Data processing and transformation scripts
├── outputs/              # Final tables ready for Power BI ingestion
├── docs/                 # Documentation and metadata descriptions
└── README.md
```
## ⚙️ Data Processing Workflow

The pipeline follows a structured sequence:

1. Data Ingestion

* Import raw WAVE datasets from multiple sources
* Validate file formats and schema consistency

2. Data Cleaning

* Handle missing values and inconsistencies
* Standardize variable names and formats
* Remove duplicates and invalid entries

3. Data Transformation

* Aggregate or reshape data where necessary
* Harmonize spatial and temporal scales
* Derive key indicators relevant for surveillance and analysis

4. Data Validation

* Perform sanity checks and summary statistics
* Ensure alignment with expected distributions and ranges
* Export for Visualization

6. Generate clean, structured tables

7. Save outputs in formats compatible with Power BI (e.g., .csv, .xlsx)