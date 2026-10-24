# Retail Sales Data Analysis — UCI Online Retail

## Project Overview
An end-to-end real-world retail analytics project using the **UCI Online Retail** transactional dataset. The analysis covers data cleaning, revenue trends, product performance, customer behavior, geographic demand, and cancellations/returns.

## Objective
Turn raw retail transactions into actionable business insights using Python-based exploratory data analysis.

## Dataset
- **Source:** UCI Machine Learning Repository — Online Retail
- **Records:** 541,909
- **Period:** 1 Dec 2010 to 9 Dec 2011
- **Domain:** Business / Retail
- **License:** CC BY 4.0
- **DOI:** 10.24432/C5BW33

The notebook loads the dataset programmatically with `ucimlrepo`, avoiding storage of the 22.6 MB source workbook in GitHub.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Workflow
1. Dataset loading and inspection
2. Data-quality checks
3. Duplicate and cancellation handling
4. Date/time feature engineering
5. Revenue calculation
6. Monthly revenue trend
7. Top-product analysis
8. Country-level performance
9. Customer revenue and order analysis
10. Returns/cancellation analysis
11. Weekday and hourly patterns
12. Correlation analysis
13. Business conclusions

## Repository Structure
```text
Retail-Sales-Data-Analysis/
├── Retail_Sales_Data_Analysis.ipynb
├── Retail_Sales_Project_Report.pdf
└── README.md
```

## How to Run
```bash
pip install ucimlrepo pandas numpy matplotlib seaborn openpyxl jupyter
jupyter notebook Retail_Sales_Data_Analysis.ipynb
```

The notebook fetches the UCI dataset using:
```python
from ucimlrepo import fetch_ucirepo
online_retail = fetch_ucirepo(id=352)
```

## Expected Outcome
The project applies data science skills to a real business problem and produces visual, business-oriented conclusions suitable for a student data analytics portfolio.

## Author
**Rohit Labana**  
B.Tech CSE — Parul University

## Dataset Citation
Chen, D. (2015). Online Retail [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5BW33.
