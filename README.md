
# customer_behavior_analysis
data analysis project showcasing customer behavior analysis using python, sql, and power bi


# 📊 Data Analysis Project

## Overview

This project demonstrates an end-to-end **data analysis workflow**, from loading and cleaning raw data to extracting insights, performing SQL analysis, and presenting the results through an interactive **Power BI dashboard** and business report.

The project focuses on transforming raw data into meaningful insights that can support **data-driven decision-making**.

---

## Dataset

The dataset contains structured business data used to perform exploratory analysis, data cleaning, SQL analysis, and visualization.

The analysis covers areas such as:

* Data quality and consistency
* Trends and patterns
* Key performance indicators (KPIs)
* Category and segment analysis
* Business performance
* Relationships between different variables

> **Dataset:** customer_shopping_behavior.

---

## Tools & Technologies

| Tool                                | Purpose                                 |
| ----------------------------------- | --------------------------------------- |
| **Python**                          | Data loading, cleaning and analysis     |
| **Pandas**                          | Data manipulation and preprocessing     |
| **NumPy**                           | Numerical analysis                      |
| **Matplotlib / Seaborn**            | Data visualization and EDA              |
| **PostgreSQL / MySQL / SQL Server** | SQL-based data analysis                 |
| **Power BI**                        | Interactive dashboard and visualization |
| **Gamma**                           | Presentation / PPT creation             |
| **Jupyter Notebook**                | Python analysis and documentation       |
| **GitHub**                          | Project version control and portfolio   |

---

## Project Workflow

### 1. Load the Dataset

The dataset was imported into Python using Pandas.

```python
import pandas as pd

df = pd.read_csv("dataset.csv")
```

Initial checks were performed to understand:

* Number of rows and columns
* Data types
* Missing values
* Duplicate records
* Basic statistics

---

### 2. Exploratory Data Analysis (EDA)

EDA was performed to understand the structure and characteristics of the data.

Key activities included:

* Descriptive statistics
* Distribution analysis
* Missing-value analysis
* Outlier identification
* Correlation analysis
* Trend analysis
* Category and segment comparisons

Visualizations were created to identify important patterns and relationships within the dataset.

---

### 3. Data Cleaning

The raw dataset was cleaned and prepared for analysis.

Cleaning steps included:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Standardizing column names
* Formatting categorical values
* Handling inconsistent records
* Identifying and treating outliers where appropriate

The cleaned dataset was then used for SQL analysis and dashboard development.

---

### 4. SQL Analysis

The cleaned data was analyzed using SQL.

SQL queries were developed and executed using:

* **PostgreSQL**
* **MySQL**
* **SQL Server**

The analysis included:

* Filtering and sorting data
* Aggregations
* `GROUP BY` analysis
* Joins
* Subqueries
* Common Table Expressions (CTEs)
* Window functions
* KPI calculations
* Ranking and trend analysis

Example:

```sql
SELECT
    category,
    SUM(sales) AS total_sales,
    AVG(sales) AS average_sales
FROM sales_data
GROUP BY category
ORDER BY total_sales DESC;
```

---

### 5. Power BI Dashboard

The analyzed data was used to build an interactive **Power BI dashboard**.

The dashboard includes:

* Key Performance Indicators (KPIs)
* Interactive charts
* Trend analysis
* Category/segment analysis
* Filters and slicers
* Summary metrics
* Business insights

The dashboard is designed to provide a clear overview of the most important findings and allow users to explore the data interactively.

---

## 📈 Dashboard

The Power BI dashboard provides an interactive view of the analysis and highlights the key metrics and trends identified during the project.

**Key dashboard features:**

* KPI cards
* Bar and column charts
* Line charts
* Donut/pie charts where appropriate
* Interactive slicers
* Drill-down analysis
* Comparative performance views

---

## Results & Key Insights

The analysis generated several business insights from the dataset.

Key findings include:

* Identified important trends and patterns in the data
* Highlighted top-performing and underperforming categories
* Identified relationships between key business variables
* Evaluated important KPIs and performance metrics
* Improved data quality through systematic cleaning
* Used SQL to answer business-focused analytical questions
* Presented findings through an interactive Power BI dashboard

---

## 📑 Project Report

A detailed report was created to document the complete analysis process.

The report covers:

1. Project objective
2. Dataset description
3. Data preparation
4. Exploratory data analysis
5. Data cleaning
6. SQL analysis
7. Power BI dashboard
8. Key findings
9. Business recommendations
10. Conclusion

---

## 🖥️ Presentation

A presentation was created using **Gamma** to communicate the project findings in a concise and visually engaging format.

The presentation covers:

* Business problem
* Dataset overview
* Analytical approach
* Key insights
* Dashboard highlights
* Results
* Recommendations
* Conclusion

---

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/your-repository.git
```

### 2. Navigate to the Project Folder

```bash
cd your-repository
```

### 3. Install Required Python Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Run the Python Analysis

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run the notebook to perform:

* Data loading
* EDA
* Data cleaning
* Data visualization

### 5. Run SQL Analysis

Import the cleaned dataset into your preferred database:

* PostgreSQL
* MySQL
* SQL Server

Then execute the SQL scripts provided in the `SQL` folder.

### 6. Open the Power BI Dashboard

Open the `.pbix` file in **Power BI Desktop** to explore the interactive dashboard.

---

## Project Structure

```text
Data-Analysis-Project/
│
├── Dataset/
│   └── dataset.csv
│
├── Python/
│   └── data_analysis.ipynb
│
├── SQL/
│   ├── postgresql_queries.sql
│   ├── mysql_queries.sql
│   └── sql_server_queries.sql
│
├── PowerBI/
│   └── dashboard.pbix
│
├── Report/
│   └── project_report.pdf
│
├── Presentation/
│   └── project_presentation.pdf
│
└── README.md
```

---

## Conclusion

This project demonstrates a complete **end-to-end data analysis process**, combining Python, SQL, and Power BI to transform raw data into actionable insights.

It showcases practical skills in:

* Data Cleaning
* Exploratory Data Analysis
* Python
* SQL
* PostgreSQL
* MySQL
* SQL Server
* Data Visualization
* Power BI
* Business Reporting
* Data Storytelling

---

## Skills Demonstrated

**Python | Pandas | NumPy | EDA | Data Cleaning | SQL | PostgreSQL | MySQL | SQL Server | Power BI | Data Visualization | Business Analysis | Data Storytelling**





