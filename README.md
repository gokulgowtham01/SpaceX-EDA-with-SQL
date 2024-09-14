# SpaceX-EDA-with-SQL


## Overview
This project involves analyzing SpaceX launch data using SQL queries on an SQLite database. The dataset is loaded into SQLite from a CSV file and various SQL queries are executed to extract insights.

## Setup
Load Data:

Dataset: SpaceX Data CSV
Data is imported into SQLite and stored in the SPACEXTBL table.

## SQL Queries:

Drop and Create Tables: Drop an existing table and create a new one with non-null dates.
Distinct Launch Sites: List unique launch sites.
Total Payload Mass: Sum of payload mass for NASA (CRS).
Average Payload Mass: Average payload mass for booster version 'F9 v1.1'.
First Success Date: Earliest date with a successful landing on the ground pad.
Booster Version and Payload Mass: Booster version for successful landings with specific payload mass ranges.
Mission Outcome Count: Count of each mission outcome.
Max Payload Mass: Booster version with the maximum payload mass.
Failures in 2015: Monthly breakdown of failures on drone ships in 2015.
Landing Outcomes Over Time: Count of landing outcomes between specified dates.

## Dependencies
pandas
sqlite3
sql magic extension
Ensure these libraries are installed and the SQL magic extension is enabled in your environment.
