# SmartSpend AI 💡

SmartSpend AI is an intelligent financial analytics dashboard that transforms raw transaction data into actionable insights using data visualization and machine learning concepts.

## Features
- Secure Sign In / Register
- Persistent User Profiles
- Interactive KPI Dashboard
- Predictive Spending Charts
- Anomaly & Risk Detection
- Glassmorphic UI Design

## Tech Stack
- Flask
- HTML / CSS / JavaScript
- Chart.js
- LocalStorage Authentication

## Dataset & Analysis

This project uses sample spending data located in the `data/` directory to demonstrate
expense analysis and machine learning functionality.

### Data Overview
- The dataset contains anonymized transaction records such as:
  - Date
  - Category
  - Amount
  - Description

### How the data is used
- The Flask backend loads the dataset from the `data/` folder
- Data is processed using Python (Pandas, NumPy)
- Machine learning models analyze spending patterns and trends
- Results are displayed on the web dashboard

### For reviewers
To analyze the spending data:
1. Navigate to the `data/` folder in this repository
2. Open the CSV file(s) to view raw transaction data
3. Run the application to see how insights are generated from the data


## Run Locally
```bash
pip install -r requirements.txt
python app.py
