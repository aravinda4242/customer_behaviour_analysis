# customer_behaviour_analysis
Data Analytics Project showacasing customer behavior analysis using python, SQL, Power Bi
# 📊 Data Analytics Project

## 📌 Overview

This project focuses on analyzing a real-world dataset to identify **business insights, customer behavior, sales trends, and key performance indicators**.

The project follows an end-to-end data analytics workflow:

**Python → Data Cleaning → Exploratory Data Analysis → SQL/MySQL → Power BI → Report → Presentation**

The analysis helps transform raw data into meaningful insights that can support **data-driven business decisions**.

---

## 📂 Dataset

The dataset contains information related to customers, products, purchases, sales, and other relevant business attributes.

### Dataset Activities

* Loaded the dataset using Python
* Checked data types and structure
* Identified missing values and duplicates
* Analyzed numerical and categorical columns
* Performed data quality checks
* Cleaned and prepared the data for analysis

---

## 🛠️ Tools & Technologies

| Tool                     | Purpose                                               |
| ------------------------ | ----------------------------------------------------- |
| **Python**               | Data loading, cleaning, and analysis                  |
| **Pandas**               | Data manipulation and preprocessing                   |
| **NumPy**                | Numerical analysis                                    |
| **Matplotlib / Seaborn** | Data visualization                                    |
| **MySQL / SQL Server**   | SQL-based data analysis                               |
| **SQL**                  | Filtering, aggregation, joins, and analytical queries |
| **Power BI**             | Interactive dashboard development                     |
| **Excel**                | Data inspection and supporting analysis               |
| **Gamma**                | Project presentation                                  |
| **GitHub**               | Project documentation and version control             |

---

# 🔄 Project Steps

## 1. Data Loading

The dataset was loaded into Python using **Pandas**.

python
import pandas as pd

df = pd.read_csv("dataset.csv")

print(df.head())
print(df.info())


The initial analysis was performed to understand the dataset structure, columns, data types, and number of records.

---

## 2. Exploratory Data Analysis (EDA)

EDA was performed to understand patterns and relationships within the data.

### Key activities:

* Dataset overview
* Descriptive statistics
* Missing value analysis
* Duplicate identification
* Distribution analysis
* Categorical value analysis
* Correlation analysis
* Identification of trends and patterns

---

## 3. Data Cleaning

The dataset was cleaned before performing detailed analysis.

### Cleaning activities:

* Handled missing values
* Removed duplicate records
* Corrected data types
* Standardized column values
* Checked inconsistent or invalid data
* Prepared clean data for SQL and Power BI

---

## 4. SQL / MySQL / SQL Server Analysis

The cleaned dataset was imported into a SQL database for further analysis.

### SQL concepts used:

* SELECT
* WHERE
* GROUP BY
* ORDER BY
* Aggregate functions
* JOIN
* Subqueries
* CASE
* Filtering
* Data aggregation
* Analytical queries

Example:

sql
SELECT 
    Category,
    SUM(Sales) AS Total_Sales
FROM sales_data
GROUP BY Category
ORDER BY Total_Sales DESC;


SQL analysis was used to identify important business trends and generate insights from the data.


# 📊 Power BI Dashboard

An interactive **Power BI dashboard** was created to present the analysis visually.

### Dashboard includes:

* Key Performance Indicators (KPIs)
* Sales and revenue analysis
* Customer analysis
* Product/category performance
* Trend analysis
* Interactive charts
* Filters and slicers
* Business insights

The dashboard allows users to interact with the data and quickly understand important performance metrics.

---

## 📈 Dashboard Highlights

The dashboard provides a visual view of:

* Overall business performance
* Top-performing products/categories
* Customer purchasing patterns
* Sales trends
* Revenue distribution
* Important KPIs
* Areas of improvement and growth opportunities

> **Power BI Dashboard:**
> Add your Power BI screenshots or published dashboard link here.

---

# 📄 Project Report

A detailed project report was created covering:

1. Project Overview
2. Business Problem
3. Dataset Description
4. Data Cleaning
5. Exploratory Data Analysis
6. SQL Analysis
7. Power BI Dashboard
8. Key Insights
9. Business Recommendations
10. Conclusion

---

# 🎯 Results & Insights

The analysis helped identify meaningful patterns and trends from the dataset.

### Key outcomes:

* Identified important sales and customer trends
* Analyzed product/category performance
* Identified high-performing and low-performing areas
* Used SQL to extract meaningful business information
* Built an interactive Power BI dashboard
* Converted raw data into actionable insights
* Presented findings through a structured report and presentation

The project demonstrates the ability to work with data from **raw dataset to final business insights**.

---

# 🎤 Project Presentation

A PowerPoint presentation was created using **Gamma** to summarize the project.

The presentation covers:

* Problem Statement
* Dataset
* Data Preparation
* EDA
* SQL Analysis
* Power BI Dashboard
* Key Findings
* Business Recommendations
* Conclusion

> **Presentation:** Add your Gamma presentation link here.

---

# 🚀 How to Run

### Step 1: Clone the Repository

bash
git clone https://github.com/yourusername/your-repository-name.git


### Step 2: Navigate to the Project

bash
cd your-repository-name


### Step 3: Install Required Python Libraries

bash
pip install pandas numpy matplotlib seaborn


### Step 4: Load the Dataset

Place the dataset inside the project folder and update the file path in the Python notebook/script.

### Step 5: Run the Python Analysis

Open the Jupyter Notebook or Python file and run the cells/scripts to perform:

* Data loading
* Data cleaning
* EDA
* Visualization

### Step 6: Run SQL Analysis

Import the cleaned dataset into **MySQL or SQL Server** and execute the SQL queries provided in the project.

### Step 7: Open Power BI

Open the Power BI .pbix file to view the interactive dashboard.

---

# 📁 Project Structure

text
Data-Analytics-Project/
│
├── Dataset/
│   └── dataset.csv
│
├── Python/
│   └── data_analysis.ipynb
│
├── SQL/
│   └── analysis_queries.sql
│
├── PowerBI/
│   └── dashboard.pbix
│
├── Report/
│   └── project_report.pdf
│
│
└── README.md


💡 Skills Demonstrated

* Data Analysis
* Data Cleaning
* Exploratory Data Analysis
* Python
* Pandas & NumPy
* SQL / MySQL / SQL Server
* Data Visualization
* Power BI
* Dashboard Development
* Business Intelligence
* Data Interpretation
* Report Writing
* Data Storytelling


 ⭐ Conclusion

This project demonstrates an end-to-end **Data Analytics workflow**, starting from raw data and progressing through **Python-based analysis, data cleaning, SQL querying, Power BI visualization, reporting, and presentation**.

It highlights practical skills required for an entry-level **Data Analyst / Business Intelligence** role.
