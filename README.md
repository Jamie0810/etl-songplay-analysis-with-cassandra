# Data Modeling with Cassandra
## Introduction
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

## Project Description
This project uses python to read the contents of the CSV files and then stores the data in Apache Cassandra databases. We are going to create an ETL pipeline that transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Cassandra tables.

## Files
```
.
├── event_data---------------------------* The directory of CSV files partitioned by date.
├── Project_1B_ Project_Template.ipynb---* This notebook contains detailed instructions on this project step by step.
└── event_datafile_new.csv---------------* The CSV composed by all files from event_data.
```

## How to Use
Launch `Project_1B_ Project_Template.ipynb` to run validation and example queries.


