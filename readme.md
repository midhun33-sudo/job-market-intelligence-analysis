## Problem Statement

This project investigates how educational qualifications, sector classification, and job role categories influence salary distribution in government job listings.

The analysis explores demand distribution across qualifications and examines how role hierarchy and sector dynamics interact with education levels to determine compensation patterns.

## Project Status
🚧 Project in Progress

Current stage: **Data Collection (Web Scraping)**

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

---

## Repository Structure

```job-market-analysis
│
├── README.md
├── data/
│ └── raw_jobs.csv
├── notebooks/
│ └── web_scraping.ipynb
```

---

## Next Steps
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Multivariate Analysis
- Insights and Visualization