# Rural-Hospital-Risk-Indicators

## Overview
This project builds a model to estimate which hospitals may be at risk of closing within 1 year. We use publicly available hospital and community data to identify patterns associated with higher risk.
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

Links to these data sources are provided above. Due to the size and update frequency, the full datasets are not included in this repository. A sample processed dataset (merged_df_sample_500.csv) is included for reference. <br>

We do not claim ownership of any third-party data used in this project. Users are responsible for complying with the terms of use and licensing of each data source. <br>

## How to Run this Project
### Step 1: Download the code
Download this repository from GitHub to your computer. <br>
### Step 2: Open the project folder
Open the folder in your terminal or coding environment.
### Step 3: Install required libraries
Run the following command to install everything you need: <br>
pip install -r requirements.txt <br>
### Step 4: Add the data <br>
ADD DETAILS TO FULL DATASET, NEED TO CIRCLE BACK <br>
### Step 5: Run the code <br>
Run the scripts in this order: <br>
1. Data Preparation <br>
2. Modeling <br>
3. Analysis <br>
These scripts will clean and combine the data, train the models, and generate results and figures. <br>
## What This Code Produces <br>
Running the code will create: <br>
1. model performance results <br>
2. feature importance outputs <br>
3. comparisons between high and low risk hospitals <br>
4. classification of hospitals into high, medium, and low risk of closure within 1 year with key ratios comparison showing what factors are driving risk relative to the average hospital <br> 
5. figures used in the final report <br>
MAYBE CREATE AN OUTPUTS FOLDER IF TIME  <br>
## Requirements  <br>
All required Python libraries are listed in requirements.txt <br>
## Notes <br>
1. The code has been cleaned and simplified for submission <br>
2. All results and figures in the report can be reproduced using this code <br>
## Team  <br>
McKenzie Boutsikakis <br>
Kostas Boutsikakis <br>
