# ETL Nba Player CSV to PostgreSQL - with several pandas technique such as split columns, add columns, drop columns and so on.

Transform dataset from Csv to Postgresql using Python-PandaSql

The purpose of this project is to extract dataset from csv online, transform with several basic technique using python pandasql and load to PostgreSQL.

Download Dataset file : https://media.geeksforgeeks.org/wp-content/uploads/nba.csv

## Goals of the Project:
  1.  Extract dataset like csv,excel,etc.
  2.  Transform using python (I used jupyter notebook) and pandas as Library. 
  3.  Load the result to PostgreSQL using SQLAlchemy library on Python.

## Materials and Methods
  1.  Bussiness Understanding : The Business Understanding phase focuses on understanding the objectives and requirements of the project. In this project, we should know about what's happening, why it's happening and who is involved in the dataset.
  2.  Data Understanding : Next is the Data Understanding phase. Adding to the foundation of Business Understanding, it drives the focus to identify, collect, and analyze the data sets that can help you accomplish the project goals. The data is consist of Name of NBA Players, Salary, Weight, height, Position .
  3.  Data Preparation : This phase, which is often referred to as “data munging”, prepares the final data set(s) for modeling. In this methods , we reading the data frame using dataframe head or subscribe. We make sure that the table, the columns and the data values are on right things.

## Lesson Results
  1.  The NBA Player dataset successfully extract from csv to panda dataframe on python. Using pd.read_csv and pointed to online website, we can read the dataset clearly.
  2.  The transformation phase is to confirm the data, and check the column names, values ​​and data format. After that, using str.split() to split columns Height into feet and inch. Adding new columns from a formula to convert feet to centimeter or meter.
  3.  We can learn about connection on The Load Phase. The connection build from dataframe to database, for this case is PostgreSQL, using to_sql code on python-pandas library. In this stage, we defined the table name, the connection name, and any other configuration such as append or replace an existing table if there is exists.
