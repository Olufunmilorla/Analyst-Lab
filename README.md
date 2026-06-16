# Analyst-Lab Netflix Analysis
A comprehensive data cleaning and exploratory data analysis project on the Netflix Titles and Online Retail dataset using SQL and Power BI, highlighting data quality improvements and actionable insights.

# Netflix Data Cleaning and Exploratory Data Analysis

## Project Overview

This project focuses on cleaning, validating, and analyzing the Netflix Titles dataset using SQL and Power BI. The objective was to transform raw data into a structured, analysis-ready format and uncover meaningful insights through exploratory data analysis and visualization.

## Tools Used

* SQL Server
* Power BI
* Microsoft Excel
* GitHub

## Dataset Information

The dataset contains information about movies and TV shows available on Netflix, including:

* Show ID
* Type (Movie/TV Show)
* Title
* Director
* Cast
* Country
* Date Added
* Release Year
* Rating
* Duration
* Genre
* Description

## Data Cleaning Process

The following cleaning operations were performed:

### Missing Values

* Identified missing values across all columns.
* Replaced missing directors with "Unknown Director".
* Replaced missing cast information with "Not Available".
* Replaced missing country values with "Unknown".
* Handled missing ratings and durations appropriately.
* Removed records with missing date information where necessary.

### Duplicate Records

* Checked for duplicate records.
* No duplicate records were found.

### Standardization

* Standardized column names.
* Standardized text formatting.
* Converted date fields into a consistent format.
* Corrected data types where required.

### Data Validation

* Validated ratings and duration fields.
* Checked for inconsistencies and anomalies.
* Verified release years and categorical values.

## Exploratory Data Analysis

The analysis focused on:

1. Movies vs TV Shows Distribution
2. Content Added by Year
3. Top Content-Producing Countries
4. Most Common Ratings
5. Most Common Genres

## Visualizations

The dashboard includes:

* Movies vs TV Shows Distribution
* Top Producing Countries
* Content Added Over Time
* Ratings Distribution
* Genre Analysis

## Key Insights

* Movies represent the majority of Netflix content.
* The United States contributes the largest number of titles.
* Netflix experienced rapid content growth between 2016 and 2020.
* TV-MA and TV-14 are the most common content ratings.
* International Movies and Dramas dominate the platform's catalog.

## Repository Contents

* Cleaned Dataset
* SQL Scripts
* Power BI Visualizations
* Project Report


