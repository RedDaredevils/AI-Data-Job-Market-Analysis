# AI & Data Job Market Intelligence System

This project started from a simple question:

“What skills and roles are actually in demand in the AI/Data industry right now?”

Instead of using static Kaggle datasets, I wanted to work with real-world live job data and build a complete analytics pipeline similar to what analysts work on in companies.

So I collected live job postings using APIs, cleaned and transformed the data using Python, stored it in SQL, analyzed hiring trends, extracted skills from job descriptions, and finally built dashboards in Power BI.

---

## What This Project Does

- Collects real-world AI/Data job postings using APIs
- Cleans and preprocesses messy real-world data
- Performs salary and hiring trend analysis
- Extracts in-demand skills from job descriptions using NLP-style processing
- Stores data in SQL for analytics queries
- Visualizes insights using Power BI dashboards

---

## Tech Stack

- Python
- Pandas
- SQL (SQLite)
- Power BI
- Matplotlib
- REST APIs
- NLP / Text Processing

---

## Project Workflow

### 1. Data Collection
Used APIs to collect live job postings for roles like:
- Data Analyst
- Data Scientist
- ML Engineer
- AI Engineer
- Power BI Developer

### 2. ETL Pipeline
Built an ETL workflow:
- Extract → API data
- Transform → cleaning & preprocessing
- Load → SQL database

### 3. Data Cleaning
Handled:
- missing values
- duplicate jobs
- inconsistent salary fields
- messy text data

### 4. Exploratory Data Analysis
Analyzed:
- top hiring companies
- salary trends
- location-wise demand
- role-wise demand

### 5. Skill Extraction
Extracted technical skills from job descriptions such as:
- Python
- SQL
- Power BI
- AWS
- Machine Learning
- TensorFlow

### 6. SQL Analytics
Used SQL queries to analyze:
- hiring trends
- salary insights
- company demand
- contract types

### 7. Power BI Dashboard
Built interactive dashboards for:
- Executive overview
- Salary analysis
- Hiring trends
- Skill demand analysis

---

## Some Key Insights

- SQL and Python appeared in a large percentage of job descriptions
- Data Analyst roles had the highest volume of openings
- AI/ML roles showed higher average salaries
- Certain companies consistently hired across multiple locations

---

## Challenges Faced

One of the biggest challenges was dealing with real-world data.

Unlike clean tutorial datasets:
- API responses were inconsistent
- salary fields were missing in many jobs
- job descriptions were messy
- some APIs had authentication/rate-limit issues

Working through these problems helped me understand real ETL and analytics workflows much better.

---

## Future Improvements

Things I want to improve later:
- automate daily data collection
- add streaming/live dashboards
- use advanced NLP for skill extraction
- deploy dashboards online
- compare hiring trends across countries

---

## Author

Adeel Umar