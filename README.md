# ETL-pipeline-using-Python-AND-Postgres
Project that I followed on an online platform in their virtual environment  will need to define fact and dimension tables for a star schema for a particular analytic focus, and write an ETL pipeline that transfers data from files in two local directories into these tables in Postgres using Python and SQL.
Schema for Song Play Analysis

Fact Table

songplays records in log data associated with song plays

Dimension Tables

users in the app

songs in music database

artists in music database

time: timestamps of records in songplays broken down into specific units

Project Design

Database Design is very optimized because with a ew number of tables and doing specific join, we can get the most information and do analysis

ETL Design is also simplified have to read json files and parse accordingly to store the tables into specific columns and proper formatting
