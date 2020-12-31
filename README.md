# Data-Modeling-with-Apache-Cassandra

## Datasets
The Dataset used for this project will be the event_data csv files that are partitioned by date.

## Objective
The event_data.csv files will be processed to create a denormalized dataset which will be modeled to answer the customer specific queries

## Steps to create an Apache Cassandra database and run the ETL Pipeline
1. Run the logic written out in part 1 to iterate through each event file and creare a csv file object
2. Create a Keyspace
3. Write out your Create Table statements
4. Load the data with Insert statement for the created tables
5. Write out Drop table statements in case you need to make changes to a incorrectly written CREATE statements

