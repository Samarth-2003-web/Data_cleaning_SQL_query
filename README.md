# Data_cleaning_SQL_query

 Project Overview
This project focuses on cleaning and analyzing a real-world dataset of Netflix titles using Python (pandas) and SQL (SQLite). The goal is to demonstrate strong data cleaning skills, SQL querying, and integration of SQL with pandas.

## Tools Used
Python: pandas, numpy, sqlite3

SQL: SQLite queries run inside Jupyter Notebook

Jupyter Notebook: for interactive data analysis

GitHub: project version control


## Dataset 
Source: Netflix Titles dataset on Kaggle

Contains details of Netflix movies and TV shows such as:

title, director, cast, country, release_year, duration, rating, description, etc.


## Data Cleaning Steps
Removed unnecessary columns (like description where not used)

Handled missing values using:

"Unknown" or "Not available" for textual nulls

dropna() for critical fields like date_added

Cleaned inconsistent formats (e.g., trimmed whitespace from country names)

Exploded multi-country rows into individual rows for accurate grouping

Converted duration into numeric minutes for movies

## SQL Queries Included
Easy: Count shows, unique types, group by type

Medium: Filter by year, top countries, subqueries

Hard: Window functions, CTEs, CASE statements for categorization

SQL queries were run using pd.read_sql_query() with SQLite inside Python

## Key Insights
Top countries producing content on Netflix

Most common content ratings and durations

Distribution of shows over time

Content type trends (Movie vs TV Show)
