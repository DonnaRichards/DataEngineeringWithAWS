# Project 1 - Data Modeling with Apache Cassandra

## Project Details

### Datasets
For this project, you'll be working with one dataset: event_data. The directory of CSV files partitioned by date. Here are examples of filepaths to two files in the dataset:

event_data/2018-11-08-events.csv
event_data/2018-11-09-events.csv

### Project Template
To get started with the project, go to the workspace on the next page, where you'll find the project template (a Jupyter notebook file). You can work on your project and submit your work through this workspace.

The project template includes one Jupyter Notebook file, in which:

you will process the event_datafile_new.csv dataset to create a denormalized dataset
you will model the data tables keeping in mind the queries you need to run
you have been provided queries that you will need to model your data tables for
you will load the data into tables you create in Apache Cassandra and run your queries

### Project Steps

Below are steps you can follow to complete each component of this project.

- Modeling your NoSQL database or Apache Cassandra database
- Design tables to answer the queries outlined in the project template
- Write Apache Cassandra CREATE KEYSPACE and SET KEYSPACE statements
- Develop your CREATE statement for each of the tables to address each question
- Load the data with INSERT statement for each of the tables
- Include IF NOT EXISTS clauses in your CREATE statements to create tables only if the tables do not already exist. We recommend you also include DROP TABLE statement for each table, this way you can run drop and create tables whenever you want to reset your database and test your ETL pipeline
- Test by running the proper select statements with the correct WHERE clause
- Build ETL Pipeline
- Implement the logic in section Part I of the notebook template to iterate through each event file in event_data to process and create a new CSV file in Python
- Make necessary edits to Part II of the notebook template to include Apache Cassandra CREATE and INSERT statements to load processed records into relevant tables in your data model
- Test by running SELECT statements after running the queries on your database

## Checklist:

### ETL Pipeline Processing
Student completes the ETL pipeline procedures.
Student uses the correct datatype for each Cassandra CREATE statement.

### Data Modeling

Student creates correct data models for the queries they need to run.
Student can set up the data model correctly to generate the exact responses posed in the questions.
Student has given careful thought to how the data is modeled in the table and the sequence and order in which data is partitioned, inserted and retrieved from the table.
Student models the data by using appropriate table names.

### PRIMARY KEYS
The PRIMARY key for each table should uniquely identify each row in each of the tables

### Presentation
Student provides responses to the questions.
Students notebook code should be clean and modular.

### Suggestions to Make Your Project Stand Out
You can add description of your PRIMARY KEY and how you arrived at the decision to use each for the query
Use Panda dataframes to add columns to your query output

## Reviewer Note:

Dear student,

Excellent job on this project! You've implemented all three tables accordingly and successfully completed this project. 👏👏

You've created all three tables with correct data types and excellent choices of primary keys.
The notebook is clean and organized, all tables have a description of how the primary key was chosen and you've selected the necessary columns to answer the three questions.
The tables have proper names and the column's sequence reflects how the tables are partitioned.
I hope you've enjoyed and learned a lot from it.

Good luck with your next Data endeavors!😃