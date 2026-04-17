## Problem Statement

This project investigates how educational qualifications, sector classification, and job role categories influence salary distribution in government job listings.

The analysis explores demand distribution across qualifications and examines how role hierarchy and sector dynamics interact with education levels to determine compensation patterns.

## Project Status
🚧 Project in Progress

Completed stage: **Data Collection (Web Scraping)**
Current stage: **Data Cleaning an Feature Engineering**

---

## Data Collection
Job listings were collected using web scraping techniques from a public job listing portal.

- Pages scraped: 43
- Total job records collected: 1028
- Data fields collected:
  - Job Title
  - Job Link
  - Job Type
  - Qualification
  - Salary

The scraped dataset is stored in the `data/` directory.

## Feature Engineering


---

## Repository Structure

```job-market-analysis
|
├── [README.md](http://readme.md/) 
├── requirements.txt
│
├── data/
│   ├── raw_jobs.csv 
│   └── cleaned_jobs_data.csv
|   |-- Trimmer_jobs_data.csv 
│
├── notebooks/
│   ├── 01_web_scraping.ipynb 
│   ├── 02_data_cleaning_feature_engineering.ipynb 
|   |-- 03_data_Description_analysis.ipynb
```

---

## Next Steps
- Multivariate Analysis
- Insights and Visualization