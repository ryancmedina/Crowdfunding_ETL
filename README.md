# Crowdfunding_ETL
#### Dotan Barak 
#### Ifrah
#### Randall
#### Ryan
#### DU Data Analytics Project 2 | February 2025

## Summary of Instructions
* Create the Category and Subcategory DataFrames
* Create the Campaign DataFrame
* Create the Contacts DataFrame
* Create the Crowdfunding Database

## Contents
* README.md
* ETL_Mini_Project_Starter_Code.ipynb
* PgAdmin4_Database
    * QuickDBD
    * Schema_crowdfunding_db.sql
    * Screenshot_SELECT * FROM category;
    * Screenshot_SELECT * FROM subcategory;
    * Screenshot_SELECT * FROM contacts;
    * Screenshot_SELECT * FROM campaign;
* Resources
    * campaign.csv
    * category.csv
    * contacts.csv
    * subcategory.csv
    * contacts.xlsx
    * crowdfunding.xlsx

## Resources
* Class instruction and activities
* Starter content: initial Jupyter Notebook and .xlsx data
* Bootcampspot instructions
https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.merge.html
https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.html
https://numpy.org/doc/stable/reference/generated/numpy.arange.html



## Detailed Project Requirements
* A Category DataFrame is Created 
* The DataFrame contains a "category_id" column that has entries going sequentially from "cat1" to "catn", where n is the number of unique categories 
* The DataFrame has a "category" column that contains only the category titles 
* The category DataFrame is exported as category.csv 
* A Subcategory DataFrame is Created 
* The DataFrame contains a "subcategory_id" column that has entries going sequentially from "subcat1" to "subcatn", where n is the number of unique subcategories 
* The DataFrame contains a "subcategory" column that contains only the subcategory titles 
* The subcategory DataFrame is exported as subcategory.csv 
* A Campaign DataFrame is Created 
The DataFrame has the following columns: 
* A "cf_id" column
* A "contact_id" column
* A "company_name" column
* A "description" column
* A "goal" column that is a float data type
* A "pledged" column that is a float data type
An "outcome" column
* A "backers_count" column
* A "country" column
* A "currency" column
* A "launch_date" with the UTC times converted to the datetime format
* An "end_date" with the UTC times converted to the datetime format
* A "category_id" column that contains the unique identification numbers matching those in the "category_id" column of the category DataFrame
* A "subcategory_id" column that contains the unique identification numbers matching those in the "subcategory_id" column of the subcategory DataFrame
The campaign DataFrame is exported as campaign.csv 
* A Contacts DataFrame is Created 
The DataFrame has the following columns: 
* A "contact_id" column
* A "first_name" column
* A "last_name" column
An "email" column
* The contacts DataFrame is exported as contacts.csv 
* A Crowdfunding Database is Created 
* A database schema labeled, crowdfunding_db_schema.sql is created 
* A crowdfunding_db is created using the crowdfunding_db_schema.sql file 
* The database has the appropriate primary and foreign keys and relationships 
Each CSV file is imported into the appropriate table without errors 
* The data from each table is displayed using a SELECT * statement 
