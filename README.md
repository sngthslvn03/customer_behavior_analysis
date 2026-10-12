# customer_behavior_analysis
data analytics project showcasing customer behavior analysis using python , sql and powerbi.
# 📊 Data Analytics Project: End-to-End Sales Analysis

## 1. Overview

This project demonstrates an end-to-end data analytics workflow, from loading and cleaning raw data to extracting insights, writing SQL queries, building an interactive Power BI dashboard, and presenting findings through a report.

The objective is to identify sales trends, understand customer behaviour, evaluate business performance, and communicate actionable insights using industry-relevant data analytics tools.

## 2. Dataset

- **Dataset:** customer_shopping_analysis.csv
- **Source:** [[Insert dataset source or link]](https://github.com/amlanmohanty1/customer-trends-data-analysis-SQL-Python-PowerBI/blob/main/customer_behavior_sql_queries.sql)
- **Format:** CSV 
- **Key attributes:** Customer ID, age group, product category, sales, quantity, order date, and other relevant business metrics.


## 3. Tools & Technologies

- **Python:** Data loading, manipulation, and exploratory data analysis.
- **Pandas & NumPy:** Data cleaning and transformation.
- **Matplotlib & Seaborn:** Data visualisation and trend analysis.
- **SQL:** Data querying, aggregation, filtering, and business analysis.
- **PostgreSQL / MySQL / SQL Server:** Relational database management.
- **Power BI:** Interactive dashboards, KPIs, and business insights.
- **Gamma:** Presentation and report creation.
- **Git & GitHub:** Version control and project documentation.

## 4. Project Workflow

### Step 1: Data Loading
- Imported the dataset using Python.
- Examined the dataset structure, column names, and data types.
- Assessed data completeness and quality.

### Step 2: Exploratory Data Analysis (EDA)
- Analysed numerical and categorical variables.
- Identified trends, patterns, and potential anomalies.
- Explored customer demographics and sales performance.
- Created visualisations to support initial findings.

### Step 3: Data Cleaning
- Handled missing and duplicate records.
- Corrected data types and inconsistent values.
- Standardised column names and formats.
- Prepared a clean dataset for SQL analysis and reporting.

### Step 4: SQL Analysis
- Loaded the cleaned data into a relational database.
- Used filtering, grouping, sorting, and aggregate functions.
- Applied joins and subqueries where required.
- Answered business questions related to sales, customers, and product performance.

### Step 5: Power BI Dashboard
- Connected Power BI to the cleaned dataset.
- Developed KPIs and interactive visualisations.
- Analysed sales performance across relevant dimensions, such as product categories, time periods, and customer demographics.
- Added filters and slicers for interactive exploration.

### Step 6: Reporting & Presentation
- Summarised key findings and business insights.
- Prepared a structured report documenting the methodology and results.
- Created a presentation using Gamma to communicate findings and recommendations.

## 5. Dashboard

The Power BI dashboard provides an interactive view of business performance.

**Key dashboard components:**
- Total Sales and other relevant KPIs.
- Sales trends over time.
- Sales by product category.
- Customer demographic analysis.
- Comparative performance across relevant business segments.
- Interactive slicers and filters.

**Dashboard Preview:**  
[Insert dashboard screenshot here]

**Power BI Dashboard Link:** [Insert public dashboard link, if available]

## 6. Key Results & Insights

This section highlights the findings obtained from the analysis.

- **Sales Performance:** Identified the strongest and weakest performing categories or periods.
- **Customer Analysis:** Examined customer demographics and purchasing patterns.
- **Business Trends:** Analysed changes in performance across relevant time periods.
- **Data Quality:** Documented data quality issues and the cleaning steps used to address them.
- **Recommendations:** Proposed data-driven actions based on the observed results.

*Replace these general statements with actual findings and numerical results from your analysis. Do not report unverified metrics.*

## 7. Project Structure

```text
data-analytics-project/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── eda_and_cleaning.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── dashboard/
│   └── sales_dashboard.pbix
│
├── reports/
│   └── analysis_report.pdf
│
├── presentation/
│   └── project_presentation.pdf
│
├── requirements.txt
└── README.md
```

*The structure is a suggested template. Adjust the folders and filenames to match your repository.*

## 8. How to Run

### Prerequisites

Install Python 3.10 or later, a compatible SQL database, and Power BI Desktop. Gamma can be accessed through its web application.

### Step 1: Clone the Repository

```bash
git clone <your-repository-url>
cd data-analytics-project
```

### Step 2: Create a Virtual Environment

```bash
python -m venv .venv
```

Activate it on Windows:

```powershell
.venv\Scripts\Activate.ps1
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

Example `requirements.txt`:

```text
pandas
numpy
matplotlib
seaborn
jupyter
sqlalchemy
psycopg2-binary
```

Install a database-specific driver if you use MySQL or SQL Server instead of PostgreSQL.

### Step 4: Run the Analysis

Open Jupyter Notebook:

```bash
jupyter notebook
```

Run the notebook inside the `notebooks/` directory to perform data loading, EDA, and cleaning.

### Step 5: Execute SQL Queries

- Create the required database and table.
- Import the cleaned dataset.
- Update the database connection settings.
- Execute the queries in `sql/analysis_queries.sql`.

### Step 6: Open the Dashboard

Open `dashboard/sales_dashboard.pbix` using Power BI Desktop and configure the data source if necessary.

### Step 7: Review the Report

Open the report and presentation files to review the final findings and recommendations.

## 9. Future Improvements

- Automate data ingestion and cleaning.
- Integrate additional datasets and external APIs.
- Implement scheduled data refreshes.
- Add advanced customer segmentation and forecasting.
- Deploy the dashboard for wider business access.

## 10. Author

**Sangeeth Salvin**

- **GitHub:** https://github.com/sngthslvn03
- **LinkedIn:** https://www.linkedin.com/in/sangeethsalvin/
- **Email:** sangeethsalvin.27@gmail.com

## 11. License

This project is intended for educational and portfolio purposes. Add an appropriate open-source license if you wish to permit reuse and redistribution.

---

*This project demonstrates practical skills in Python, exploratory data analysis, SQL, data visualisation, business intelligence, and communicating data-driven insights.*
