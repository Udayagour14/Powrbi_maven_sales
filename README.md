# Sales DataAnalysis in PowerBI
## Sales &amp; inventory data for a fictitious chain of toy stores in Mexico

## Connect and profile the data
Connect to the sales, products, stores, and calendar csv files.
Review table columns, check for blank or null values, confirm that datatypes are accurately defined, and identify any primary and foreign key.
Take a moment to profile the data. How many transactions were recorded? How many stores does Maven Toys operate? What are the lowest and highest priced products?
Add calculated columns in the calendar table.

## Create a relational model
Load the tables to the data model and create relationships from the sales table to the products, stores, and calendar tables.
Take the form of a star schema, with 1:many relationships between fact and dimension tables.

## Add calculated measures & fields
Create calculated columns in the sales table to pull in ‘cost’ and ‘price’ from the products table, then use those fields to calculate revenue and profit for each transaction
Create measures to calculate the count of orders (‘total orders’), sum of revenue (‘total revenue’) and sum of profit (‘total profit’)
