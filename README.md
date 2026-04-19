# Rural-Hospital-Risk-Indicators

## Overview
This project builds a model to estimate which hospitals may be at risk of closing within 1 year. We use publicly available hospital and community data to identify patterns associated with higher risk. The model is designed to support policymakers and stakeholders in identifying hospitals that may require monitoring or targeted intervention.
## Repository Structure Section
```
data/ <br>
  raw/ <br>
    Cost Reports.zip <br>
    Provider of Service_sample.zip <br>
    UNC Closures-Database.xlsx <br>
  processed/ <br>
    merged_data.csv.gz <br>
Rural Hospital Risk Indicators Clean.ipynb <br>
Rural Hospital Risk Indicators Processed.ipynb <br>
requirements.txt <br>
Project Report - Rural Hospital Risk Indicators.pdf <br>
README.md <br>
```
### Report:
Project Report - Rural Hospital Risk Indicators.pdf is included in this repository <br>
### Code:
Rural Hospital Risk Indicators Processed.ipynb - main notebook used to reproduce modeling, analysis, and figures <br>
Rural Hospital Risk Indicators Clean.ipynb - full data acquisition and preprocessing workflow <br>
### Raw Data (data/raw/):
This folder contains original datasets used in the project and is used by the clean notebook <br>
1. Cost Reports.zip: full CMS Hospital Provider Cost Report (2013-2023) data <br>
2. Provider of Service_sample.zip: sample CMS Provider of Service Q4 files (2013-2023) data <br>
3. UNC Closures-Database.xlsx: full UNC Rural Hospital Closure Dataset data <br>
### Processed Data (data/processed/):
This folder contains a merged and fully clean version of all the combined raw source files and includes engineered features and final labels. It is used by the processed notebook to reproduce all results and figures <br>
1. merged_data.csv.gz: full data
### Data Access Statement:
This project uses publicly available datasets, including: <br>
1. CMS Hospital Provider Cost Report link: https://data.cms.gov/provider-compliance/cost-reports/hospital-provider-cost-report/data <br>
2. CMS Provider of Services link: https://data.cms.gov/provider-characteristics/hospitals-and-other-facilities/provider-of-services-file-quality-improvement-and-evaluation-system/data <br>
3. UNC Rural Hospital Closure link: https://www.shepscenter.unc.edu/programs-projects/rural-health/rural-hospital-closures/ <br>
<br>
Due to GitHub file size constraints: <br>
- A sample version of the Provider of Services dataset is included <br>
- A processed dataset is provided to allow reproduction of results <br>
- The full datasets can be downloaded using the links above <br>
<br>
#### We do not claim ownership of any third-party data used in this project. 
<br>

## How to Run this Project
### Step 1: Download the code
Download this repository from GitHub. <br>
### Step 2: Open the project folder
Open the project folder in your preferred coding environment. <br>
### Step 3: Install required libraries
Run the following command to install everything you need: pip install -r requirements.txt <br>
### Step 4: Run the notebook <br>
#### Option 1
Run the notebook 'Rural Hospital Risk Indicators Processed.ipynb' <br>
This notebook: <br>
- Uses the preprocessed dataset (data/processed/merged_data.csv.gz) <br>
- Reproduces all modeling results and figures from the report <br>
- Does not require rebuilding the dataset from the raw files <br>
#### Option 2
Run the notebook 'Rural Hospital Risk Indicators Clean.ipynb' <br>
This notebook: <br>
- Uses the raw dataset (data/raw/) <br>
- Performs full data cleaning, merging, and feature engineering <br>
- Recreates the final modeling dataset using the provided sample data <br>
- Results will not exactly match the final report due to the use of sample data <br>
## What This Code Produces <br>
Running the code will create: <br>
1. model performance metrics <br>
2. feature importance analysis <br>
3. comparisons between high and low risk hospitals <br>
4. hospital level risk classification (high/medium/low) <br>
5. key ratio comparisons showing drivers of risk relative to average hospitals  <br>
6. figures used in the final report <br>
## Requirements  <br>
All required Python libraries are listed in requirements.txt <br>
## Notes <br>
1. The code has been cleaned and simplified for submission <br>
2. All results and figures in the report can be reproduced using this code <br>
3. Data preprocessing has been separated to improve clarity and reproducibility  <br>
## Team  <br>
McKenzie Boutsikakis <br>
Kostas Boutsikakis <br>
