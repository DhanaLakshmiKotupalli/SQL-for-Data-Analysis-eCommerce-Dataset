This project demonstrates how to perform SQL-based data analysis using an eCommerce dataset. The entire analysis was done in Google Colab using SQLite, with the data provided as .csv files.

## Dataset Tables Used
- customer – Customer details

- product – Product information including price

- orders – Order metadata (date, customer, etc.)

- orderitem – Items in each order (product, quantity)

## Tools Used
- Google Colab

- SQLite (via sqlite3 module)

- Pandas for loading and displaying data

- Matplotlib and Seaborn (optional) for visualizations

## Objectives Completed
### 1. Data Loading & Setup

- Uploaded .csv files to Colab

- Loaded them into an SQLite in-memory database

### 2. SQL Analysis Tasks

- Top 5 customers by spending

- Monthly sales trend

- Most popular products by quantity

- Customer order summary (created as a SQL view)

### 3. SQL Techniques Used

- SELECT, WHERE, GROUP BY, ORDER BY

- Aggregate functions: SUM, COUNT, ROUND

- JOINs across multiple tables

- Creating SQL VIEWs for summary analysis

## Deliverables
- SQL queries used (in .txt file)

- Google Colab notebook (.ipynb)

- Screenshots of output

- Dataset (.csv files for 4 tables)

## How to Run
- Open the Google Colab notebook

- Upload the 4 .csv files

- Run all cells step-by-step

- View the SQL outputs inline
