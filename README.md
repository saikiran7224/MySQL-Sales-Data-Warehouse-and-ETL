# Sales Data Warehouse (ETL Pipeline)

A simple yet effective ETL (Extract, Transform, Load) pipeline built with Python, Pandas, and SQLAlchemy to process sales data and load it into a MySQL data warehouse.

---

## 📋 Project Overview

This project demonstrates a basic Sales Data Warehouse implementation featuring:
* **Staging Table:** For raw data ingestion.
* **Fact Table:** With calculated business metrics.
* **Data Transformation:** Automated total amount calculation.
* **Database Connectivity:** Seamless loading into a MySQL data warehouse.

---

## 🛠 Technologies Used

* **Python 3.13**
* **Pandas** - Data manipulation and cleaning
* **SQLAlchemy** - Database connection & ORM
* **PyMySQL** - MySQL database driver for Python
* **MySQL** - Data Warehouse storage

---

## 📁 Project Structure

```text
sales-dw-pipeline/
├── sales_data.csv              # Source data (Raw CSV)
├── sales_etl.ipynb             # Main Jupyter Notebook (ETL Code)
├── README.md                   # Project documentation
└── requirements.txt            # Python dependencies


