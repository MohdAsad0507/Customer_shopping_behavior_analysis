# Customer_behavior_analysis
Data analytics project showcasing customer behavior analysis using Python, SQL and Power BI.


# Project Overview

This project demonstrates a complete **end-to-end data analytics workflow**, transforming raw data into meaningful insights and interactive dashboards.

The project simulates a **real-world data analyst pipeline**, where Python is used for data processing and exploration, PostgreSQL is used for analytical queries, and Power BI is used for interactive business intelligence dashboards.

---

# Business Problem

Organizations collect large volumes of data but often struggle to convert it into actionable insights.

This project focuses on analyzing the dataset to answer important questions such as:

* What patterns and trends exist in the dataset?
* Which categories contribute the most to overall performance?
* What insights can help support data-driven decision making?

---

# Project Architecture

```
Dataset → Python (EDA + Data Cleaning) → PostgreSQL Database → SQL Analysis → Power BI Dashboard → Business Insights
```

---

# Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* SQL Query Writing
* Database Management
* Data Visualization
* Dashboard Development
* Business Insight Generation
* Analytical Reporting

---

# Dataset

The dataset used in this project contains structured data suitable for performing data analysis and visualization.

Dataset characteristics include:

* Combination of categorical and numerical variables
* Real-world issues such as missing values and inconsistent entries
* Data suitable for analytical queries and visualization


---

# Tools & Technologies

| Tool                 | Purpose                           |
| -------------------- | --------------------------------- |
| Python               | Data analysis and preprocessing   |
| Pandas               | Data manipulation                 |
| NumPy                | Numerical operations              |
| Matplotlib / Seaborn | Data visualization                |
| PostgreSQL           | SQL-based data analysis           |
| pgAdmin              | Database management               |
| Power BI             | Interactive dashboard development |
| Gamma                | Presentation creation             |
| Jupyter Notebook     | Development environment           |

---

# Project Workflow

## 1. Data Loading

The dataset is imported into Python using **Pandas** for analysis and preprocessing.

Tasks performed:

* Import dataset
* Check dataset shape and structure
* Inspect column data types
* Identify missing values

---

## 2. Exploratory Data Analysis (EDA)

EDA is performed to understand patterns, relationships, and anomalies in the dataset.

Key steps:

* Statistical summary of variables
* Distribution analysis
* Trend identification
* Correlation analysis

### Example Visualization

images/dashboard.png

## 3. Data Cleaning

To ensure data quality, the following preprocessing steps were performed:

* Handling missing values
* Removing duplicate records
* Fixing inconsistent data entries
* Converting data types

Clean data ensures accurate and reliable analysis.

---

## 4. SQL Analysis (PostgreSQL)

After cleaning, the dataset is loaded into a **PostgreSQL database** to perform analytical queries.

Key SQL operations performed:

* Aggregations
* Grouping and filtering
* KPI calculations
* Trend analysis

### Example SQL Query


images/sqlquery1.png
images/sqlquery2.png

```sql
SELECT subscription_status,
       COUNT(customer_id) AS repeat_buyers
FROM customer
WHERE previous_purchases > 5
GROUP BY subscription_status;


---

## 5. Power BI Dashboard

An interactive **Power BI dashboard** was built to visualize key insights derived from the dataset.

Dashboard features include:

* KPI indicators
* Trend analysis
* Category-level performance
* Interactive filtering

### Dashboard Preview


```
images/dashboard.png
```

---

# Key Insights

The analysis revealed several important insights, including:

* Identification of top-performing categories
* Trends observed across time periods
* Key metrics influencing overall performance
* Insights useful for data-driven decision making

---

# Project Structure

```
data-analytics-project
│
├── data
│   └── dataset.csv
│
├── notebooks
│   └── eda_analysis.ipynb
│
├── sql
│   └── analysis_queries.sql
│
├── dashboard
│   └── powerbi_dashboard.pbix
│
├── report
│   └── project_report.pdf
│
├── presentation
│   └── project_presentation.pptx
│
├── images
│   ├── dashboard.png
│   ├── sqlquery1.png
│   └── sqlquery2.png
│
└── README.md
```

---

# How to Run the Project

### 1. Clone the Repository

```
git clone https://github.com/your-username/data-analytics-project.git
```

---

### 2. Install Required Python Libraries

```
pip install pandas numpy matplotlib seaborn psycopg2
```

---

### 3. Run Jupyter Notebook

Execute the notebook to perform:

* Data loading
* Data cleaning
* Exploratory Data Analysis

---

### 4. Load Data into PostgreSQL

Import the cleaned dataset into your **PostgreSQL database** using pgAdmin.

---

### 5. Run SQL Queries

Execute SQL scripts from the `/sql` folder to perform analytical queries.

---

### 6. Open Power BI Dashboard

Open the `.pbix` file located in the `/dashboard` folder to explore the interactive dashboard.

---

# Results

This project demonstrates how raw data can be transformed into **meaningful insights through a structured analytics pipeline using Python, SQL, and Power BI**.

It highlights practical skills in **data preprocessing, database querying, visualization, and business intelligence reporting**.

---

# Author

Mohd Asad

Data Analytics Enthusiast

GitHub: https://github.com/MohdAsad0507
LinkedIn: https://linkedin.com/in/Mohd Asad
