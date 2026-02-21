# Netflix-Content-Analysis-SQL
This project analyzes Netflix’s content dataset using PostgreSQL to extract meaningful business insights about content distribution, ratings, genres, countries, and release trends. The goal was to simulate real-world business questions and answer them using structured SQL queries.

1. 📌 Project Overview

This project performs exploratory and business-focused analysis on the Netflix dataset using PostgreSQL. The objective was to simulate real-world business scenarios and extract meaningful insights about content trends, ratings distribution, genre dominance, regional production, and release growth over time.
The dataset contained inconsistencies such as comma-separated fields (country, cast, genres) and text-based duration values. These were handled using string transformation functions and type casting to ensure accurate analysis.

2. 📊 Business Problems Solved

Count total Movies vs TV Shows
Identify most common rating for Movies and TV Shows
List movies released in a specific year
Top 5 countries producing Netflix content
Longest movie available
Content added in the last 5 years
Content by specific director
TV Shows with more than 5 seasons
Count content by genre
Year-wise content release trend (India)
Top actors appearing in Indian content
Categorize content as Good/Bad based on description keywords
Content distribution by duration

3. 🛠 Technologies Used

PostgreSQL
SQL
GitHub

4. 🔧 SQL Concepts Demonstrated

Common Table Expressions (CTEs)
Window Functions (RANK() OVER (PARTITION BY))
Subqueries
Aggregation (COUNT, GROUP BY)
Date Conversion (TO_DATE, EXTRACT)
String Manipulation (STRING_TO_ARRAY, UNNEST, SPLIT_PART)
Conditional Logic (CASE WHEN)
Type Casting

5. 🗂 Dataset Information

The dataset contains Netflix content details including:
Title
Director
Cast
Country
Date Added
Release Year
Rating
Duration
Genre (Listed In)
Description

6. 📈 Key Insights

Movies dominate the platform compared to TV Shows.
Content production has increased significantly after 2015.
India ranks among the top content-producing countries.
Certain genres consistently dominate across multiple years.
Rating distribution varies significantly between Movies and TV Shows.

7. 🚀 Project Objective

To demonstrate strong SQL fundamentals and analytical problem-solving by transforming raw dataset fields and extracting actionable insights using structured queries.

8. 📎 How to Run

Import dataset into PostgreSQL
Create table using provided schema
Execute SQL queries in sequence
Release trend comparison by type

Genre dominance across years
