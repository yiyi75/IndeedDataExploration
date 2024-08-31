# Job Market Analysis (Indeed Data)

## Overview
This project provides a detailed analysis of job market trends, salary drivers, and the impact of job description sentiment on compensation. The findings offer insights for job seekers and employers, highlighting key trends in salary distribution, job roles, and market demands.

## Data Preprocessing and Cleaning
- **Salary Data**: Initially unstructured, the salary data was cleaned by extracting numeric values, converting hourly wages to yearly equivalents, and calculating average salaries for ranges.
- **Location Data**: Job locations were standardized into city and country formats.
- **Job Title Categorization**: Job titles were cleaned, standardized, and grouped into broader categories (e.g., "AI & Machine Learning," "Software Engineer") to facilitate trend analysis.

## Key Findings
- **Salary Distribution**: 
  - Most jobs offer average salaries between $80k to $220k, with full-time roles generally paying more than part-time or contract jobs (fact).
  - Hybrid roles are associated with significantly higher average salaries compared to on-site and remote jobs, with remote roles offering the lowest average pay (interesting to know!).
- **Sentiment Analysis**: 
  - Job descriptions showed varied sentiment across job types, with a weak positive correlation between sentiment polarity and salary. More fact-based (less subjective) descriptions were linked to lower salaries.
- **Textual Features**: 
  - Lasso regression identified key salary-predictive words like "product," "activation," and "integration."
  - Gradient Boosting highlighted "Software Engineer" and "Leadership" as the most influential categories in salary prediction.
- **Common Job Titles**: 
  - Frequent roles include "AI Engineer," "AI Writer and Editor," and "Activation Lead."
  - The word cloud and keyword analysis indicated strong demand for AI, leadership, and technical skills.
- **Location**: 
  - The majority of job postings are in the United States, with Palo Alto, Boston, and New York being key cities.

I enjoyed exploring and understanding the job market! Data analysis is so much fun! 😊
