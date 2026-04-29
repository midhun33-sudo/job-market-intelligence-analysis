# Government Job Market Analysis  
### How Education, Sector, and Job Roles Influence Salary Distribution

---

## 📌 Project Overview

This project analyzes government job listings to understand how **education level, sector, and job role categories influence salary distribution**.  

The study transforms raw, unstructured job data into a structured analytical dataset and explores how different factors interact to shape compensation patterns in government jobs.

---

## 🎯 Problem Statement

How do education level, sector, and job roles interact to influence salary distribution in government job listings?

---

## 🔍 Key Research Questions

- Is salary determined only by educational qualification?  
- Which sectors offer higher salary ranges?  
- What job roles are associated with higher pay?  
- Where are high-paying (elite) jobs concentrated?  
- How do qualification, sector, and role interact to influence salary?  

---

## 📂 Data Collection

- Source: Public job listing platform  
- Method: Web Scraping using Python  
- Pages scraped: 43  
- Total records collected: 1028  

### Tools Used:
- `requests`
- `BeautifulSoup`

### Extracted Fields:
- Job Title  
- Qualification  
- Salary  
- Job Type  
- Job Link  

---

## 🧹 Data Cleaning

The raw dataset contained multiple inconsistencies:

- Mixed salary formats (monthly, annual, ranges)  
- Missing salary values (~35%)  
- Unstructured text data  
- Inconsistent qualification labels  

### Cleaning Steps:
- Extracted numeric salary values using Regex  
- Converted annual salaries to monthly values  
- Handled missing values separately for analysis  
- Standardized qualification categories  
- Cleaned and structured job titles  

---

## ⚙️ Feature Engineering

Created structured features for analysis:

### Salary Features:
- `salary_minimum`  
- `salary_maximum`  
- `salary_range`  
- `salary_band`  

### Categorical Features:
- `qualification_level`  
- `sector`  
- `role_category`  

### Text Processing:
- Split job title into organization and role  
- Extracted sector and role using keyword mapping  

---

## 📊 Exploratory Data Analysis

The analysis was divided into two parts:

### 1️⃣ Demand Analysis
- Distribution of jobs across qualification levels  
- Sector-wise job demand  
- Role category distribution  

### 2️⃣ Salary Analysis
- Salary distribution patterns  
- Salary comparison across qualification, sector, and roles  
- Core vs Elite salary segmentation  

---

## 📈 Key Visualizations

- Salary Distribution Histogram  
- Qualification vs Salary (Boxplot)  
- Sector vs Salary Comparison  
- Role Category vs Salary  
- Qualification × Sector Heatmap  

---

## 🔍 Key Insights

- Undergraduate roles dominate government job demand  
- Salary is not determined by education alone  
- Sector and job role hierarchy have stronger influence on salary  
- Managerial and Officer roles show higher salary ranges  
- High-paying jobs are concentrated in PSU and Banking sectors  

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- BeautifulSoup  
- Regex  

---

## 📁 Project Structure

```
job-market-analysis/
│
├── README.md
├── requirements.txt
│
├── data/
│ ├── raw_jobs.csv
│ └── cleaned_jobs.csv
│
├── notebooks/
│ ├── 01_web_scraping.ipynb
│ ├── 02_data_cleaning_feature_engineering.ipynb
│ ├── 03_descriptive_analysis.ipynb
│ └── 04_multivariate_analysis.ipynb
│
├── images/
│ ├── salary_distribution.png
│ ├── qualification_salary.png
│ └── sector_heatmap.png
```
---

## 🚀 Future Work

- Apply machine learning models for salary prediction  
- Improve role classification using NLP techniques  
- Expand dataset across multiple job platforms  
- Perform time-based trend analysis  

---

## 👤 Author : K.Midhun Kumar

Government Job Market Analysis Project  
Focused on structured data analysis and multi-variable interaction insights