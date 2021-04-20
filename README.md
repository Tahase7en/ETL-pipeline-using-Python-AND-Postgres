# ETL-pipeline-using-Python-AND-Postgres
<b> Project Description </b>

Project that I followed on an online platform in their virtual environment  will need to define fact and dimension tables for a star schema for a particular analytic focus, and write an ETL pipeline that transfers data from files in two local directories into these tables in Postgres using Python and SQL.
Schema for Song Play Analysis
<b>Project Description </b>

<b>Schema for Song Play Analysis</b>

<b>Fact Table</b>

<b> songplays </b> records in log data associated with song plays

<b>Dimension Tables</b>

<b> users </b> in the app

<b> songs </b> in music database

<b> artists </b> in music database

<b> time: </b> timestamps of records in songplays broken down into specific units

<b>Project Design</b>

Database Design is very optimized because with a few number of tables and doing specific join, we can get the most information and do analysis

ETL Design is also simplified have to read json files and parse accordingly to store the tables into specific columns and proper formatting
<b>Project Steps</b>

Below are steps you can follow to complete the project:

<b>Create Tables</b>

Write CREATE statements in sql_queries.py to create each table.

Write DROP statements in sql_queries.py to drop each table if it exists.

Run create_tables.py to create your database and tables.

Run test.ipynb to confirm the creation of your tables with the correct columns. Make sure to click "Restart kernel" to close the connection to the database after running this notebook.

<b>Build ETL Processes</b>

Follow instructions in the etl.ipynb notebook to develop ETL processes for each table. At the end of each table section, or at the end of the notebook, run test.ipynb to confirm that records were successfully inserted into each table. Remember to rerun create_tables.py to reset your tables before each time you run this notebook.

<b>Build ETL Pipeline</b>

Use what you've completed in etl.ipynb to complete etl.py, where you'll process the entire datasets. Remember to run create_tables.py before running etl.py to reset your tables. Run test.ipynb to confirm your records were successfully inserted into each table.
