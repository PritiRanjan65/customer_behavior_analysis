# customer_behavior_analysis
data analytics project showcasing customer behavior analysis using python, sql, power Bi.



# Data Analytics Project using Python, MySQL, and Power BI

##  Project Overview

This project demonstrates an end-to-end **data analytics workflow**, covering data extraction, cleaning, transformation, storage, analysis, and visualization. The solution integrates **Python** for data processing, **MySQL** for database management, and **Power BI** for interactive dashboards and business insights.

The primary objective of this project is to convert raw data into meaningful insights that support data-driven decision-making.



##  Technologies Used

* **Python** – Data cleaning, transformation, and analysis

  * Libraries: Pandas, NumPy, Matplotlib, Seaborn
* **MySQL** – Structured data storage and query execution
* **Power BI** – Data visualization and dashboard creation
* **SQL** – Data extraction, aggregation, and analytical queries

---

##  Project Structure

```
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
├── python_scripts/
│   ├── data_cleaning.py
│   ├── data_analysis.py
│   └── mysql_connection.py
├── sql_queries/
│   └── analysis_queries.sql
├── powerbi/
│   └── dashboard.pbix
├── screenshots/
│   └── dashboard_preview.png
├── README.md
└── requirements.txt
```

---

##  Data Workflow

1. **Data Collection**
   Raw data is imported from CSV/external sources.

2. **Data Cleaning & Preprocessing (Python)**

   * Handling missing values
   * Data type correction
   * Outlier detection and removal

3. **Database Storage (MySQL)**

   * Cleaned data is stored in relational tables
   * SQL queries used for filtering and aggregation

4. **Data Visualization (Power BI)**

   * MySQL database connected to Power BI
   * Interactive dashboards created for insights

---

##  Key Insights & Features

* Trend analysis and performance metrics
* KPI-based dashboards
* Interactive slicers and filters
* Structured SQL queries for analytics
* Scalable database-driven architecture

---

##  How to Run the Project

### 1️ Clone the Repository

```bash
git clone https://github.com/your-username/data-analytics-project.git
cd data-analytics-project
```

###  Install Python Dependencies

```bash
pip install -r requirements.txt
```

###  Configure MySQL

* Create a MySQL database
* Update credentials in `mysql_connection.py`
* Import cleaned data into MySQL

###  Run Python Scripts

```bash
python python_scripts/data_cleaning.py
python python_scripts/data_analysis.py
```

###  Open Power BI Dashboard

* Open `dashboard.pbix` in Power BI Desktop
* Refresh data connection

---

## Dashboard Preview

*(Add screenshots in the `screenshots` folder)*

---

## Use Cases

* Business performance analysis
* Sales and revenue analytics
* Operational insights
* Academic and portfolio demonstration

---

## Future Enhancements

* Automation using Airflow
* Advanced analytics with Machine Learning
* Cloud deployment (AWS / Azure)
* Real-time dashboard integration

---

## Author

**Priti Ranjan Sahoo**
Data Analytics Enthusiast
Python | SQL | Power BI

---

##  License

This project is licensed under the MIT License.

---


