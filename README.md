## 1. Introduction 
Using classicmodels dataset about sale data of a company in 2003,assume the company's analytic teams is interested in understanding their business situation in the last year. We will build ETL pipelines which will transform raw data into actionable insights, store them in OLTP database (MySQL) then load data to a star schema data mart(Amazon Redshift) for enhanced data analytics capabilities.

Data include tables : <b> <i> customers, products, productlines, orders, orderdetails, payments, employees, offices </i> </b>

### Technologies used
- Python
- MySQL
- Airflow
- AWS services: Redshift (data warehouse)
- Docker