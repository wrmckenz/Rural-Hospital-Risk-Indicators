# Rural-Hospital-Risk-Indicators

## Overview
This project builds a model to estimate which hospitals may be at risk of closing within 1 year. We use publicly available hospital and community data to identify patterns associated with higher risk. The model is designed to support policymakers and stakeholder in identifying hospitals that may require monitoring or targeted intervention.
### Report:
Project Report - Rural Hospital Risk Indicators.pdf is included in this repository <br>
Project Report link:
### Code:
Rural Hospital Risk Indicators.ipynb is included in this repository <br>
### Data Access Statement:
This project uses publicly available datasets, including: <br>
1. CMS Hospital Provider Cost Report link: https://data.cms.gov/provider-compliance/cost-reports/hospital-provider-cost-report/data <br>
2. CMS Provider of Services link: https://data.cms.gov/provider-characteristics/hospitals-and-other-facilities/provider-of-services-file-quality-improvement-and-evaluation-system/data <br>
3. UNC Rural Hospital Closure link: https://www.shepscenter.unc.edu/programs-projects/rural-health/rural-hospital-closures/ <br>
Due to GitHub file size constraints, the processed dataset is provided in compressed (.csv.gz). The full dataset is included and can be loaded directly. <br>
We do not claim ownership of any third-party data used in this project. Users are responsible for complying with the terms of use and licensing of each data source. <br>
Note: The data preprocessing section in the notebook is commented out, as this file represents the final output of that pipeline.  <br>
If you would like to rerun the preprocessing steps, uncomment the relevant code in the notebook and download the raw datasets. <br>
1. CMS Hospital Provider Cost Report (2013-2023) <br>
2. CMS Provider of Service Q4 files (2013-2023) <br>
3. UNC Rural Hospital Closure Dataset <br>
After downloading, place the files in the appropriate project directory and rerun the preprocessing section to regenerate the merged dataset. <br>
## How to Run this Project
### Step 1: Download the code
Download this repository from GitHub. <br>
### Step 2: Open the project folder
Open the project folder in your preferred coding environment.
### Step 3: Install required libraries
Run the following command to install everything you need: <br>
pip install -r requirements.txt <br>
### Step 4: Add the data <br>
The processed dataset used in this project is included in compressed format as: <br>
merged_data.csv.gz <br>
This file contains the fully merged and cleaned dataset used for modeling and analysis. <br>
Note: The data preprocessing section in the notebook is commented out, as this file represents the final output of that pipeline. This allows the project to be run quickly without reprocessing the raw data. <br>
### Step 5: Run the code <br>
Run the notebook to execute the modeling and analysis steps. <br>
Note: The data preparation section is included but commented out, as the provided dataset is already processed. <br>
## What This Code Produces <br>
Running the code will create: <br>
1. model performance results <br>
2. feature importance outputs <br>
3. comparisons between high and low risk hospitals <br>
4. classification of hospitals into high, medium, and low risk of closure within 1 year with key ratios comparison showing what factors are driving risk relative to the average hospital. <br> 
5. figures used in the final report <br>
## Requirements  <br>
All required Python libraries are listed in requirements.txt <br>
## Notes <br>
1. The code has been cleaned and simplified for submission <br>
2. All results and figures in the report can be reproduced using this code <br>
## Team  <br>
McKenzie Boutsikakis <br>
Kostas Boutsikakis <br>
