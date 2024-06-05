# Adidas Sales Analysis and Visualization

## Overview
This project is based on the Adidas Sales dataset from Kaggle. The primary objectives were to clean the dataset using Python, design an appropriate SQL schema, populate PostgreSQL tables using SQLAlchemy, and perform comprehensive data analysis with visualizations.

## Objectives
- Clean the dataset in Python
- Design a schema for SQL tables based on the dataset
- Populate the PostgreSQL SQL tables with the cleaned data using SQLAlchemy
- Perform data analysis on the new tables and create visualizations where appropriate

## Skills Utilized
- Data preprocessing
- Database design
- SQL
- Python
- SQLAlchemy
- Data visualization

## Data Cleaning
The dataset was cleaned using Python, specifically leveraging pandas for tasks such as handling missing values, correcting data types, and ensuring data consistency.

## Database Design
A schema was designed to efficiently store the cleaned data in PostgreSQL. The schema includes tables for retailers, sales, and other relevant entities.

## Data Insertion
SQLAlchemy was used to insert the cleaned data into the PostgreSQL database. This allowed for efficient and scalable data management.

## Analysis and Visualizations
Various analyses were conducted on the data, and visualizations were created to highlight key insights:
- Monthly sales trends
- Sales performance by region
- Comparison of sales methods
- Leading gender type in sales per state
- Leading retailer per state

### Sample Visualizations
![Monthly Sales Trends](images/MonthlySales.png)
![Sales by Region](images/SalesByRegion.png)
![Leading Gender in Sales](images/LeadingGenderSales.png)
![Leading Retailer by State](images/LeadingRetailer.png)

## Usage
To run the project, you need to have the following installed:
- Python 3.x
- PostgreSQL
- SQLAlchemy
- pandas
- plotly
- seaborn
- matplotlib
