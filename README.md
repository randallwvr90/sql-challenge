# SQL Challenge

## Table of Contents
* [background](#background)
* [data modeling](#datamodeling)
* [data engineering](#dataengineering)
* [data analysis](#dataanalysis)

## Background
This is the SQL homework assignment for the GT Data Science Bootcamp 2021/22

## Data Modeling
I used [http://www.quickdatabasediagrams.com](http://www.quickdatabasediagrams.com) to create an ERD to visualize
the tables and relationships between tables. Please see an image of the ERD here: EmployeeSQL/images/EmployeeInfoERD.png
The code for this ERD can be found here: EmployeeSQL/EmployeeInfoERDcode.txt

## Data Engineering
Tables were created using the queries found in EmployeeSQL/schema.sql, data from the CSV files located in EmployeeSQL/data 
were imported into each table. Relations among the tables were set up to match the model created in the ERD from the 
[data modeling](datamodeling) section. 

## Data Analysis
Queries were created for each of the 8 questions in the instructions file. 

I used the "as" command to make the outputs of each query prettier. For example, the output header might read 
"Employee Number" instead of "emp\_no". 

## Thoughts
This was a great homework assignment! It gave me a better understanding of how to manipulate data using SQL and 
how to get it into a form that's easier to work with (using tables with unique rows, using junction tables to connect
them, and splitting information amongst tables - normalizing). 
