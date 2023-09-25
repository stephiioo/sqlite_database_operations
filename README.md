# sqlite_database_operations

# This is HHA 504 Homework 3: Databases part 1

## Objective: This was an introduction to the world of databases, starting with SQLite. Data was integrated and processed with Python. Pandas was utilized for exploratory data analysis, and database operations were conducted using SQLite.

## 1. Data exploration and analysis

### Stony Brook and New York Presbetarian pricing transparency datasets were imported into a Pandas DataFrame and a basic exploratory analysis was conducted using Python. This entailed data cleaning (checking for missing values, dropping all empty columns, removing duplicate rows and columns, and cleaning the columns) and exploratory analysis (checking column types, looking for outliers, creating a histogram, and creating a frequency count).

## 2. sqlite database operations

### A local SQLite database called health.db was created

### A table was created manually using CREATE TABLE SQL query. The table contained 7 columns. Four columns were numerical columns and three columns were categorical columns. One INSERT INTO SQL query was written to populate 1 row worth of fake data.

### An automatic table was created by implementing the to_sql function from Pandas to take Part 1 of this assignment into the SQLite database.
