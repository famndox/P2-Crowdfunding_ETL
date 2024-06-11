# P2-Crowdfunding_ETL

# Overview

This project involved building an ETL pipeline utilizing Python, Pandas, and Python dictionary methods to extract and transform crowdfunding data. We then loaded the dated into a postgreSQL database. This project exercised our skills data processing, transforming, and managing data bases.

# Dependencies

* Python
* Pandas
* Python dictionary methods
* PostgreSQL

# Installation

* Clone the repository
* Navigate to the project directory
* Install the required packages
* Set up PostgresSQL database using the provided schema

# Usage

* Run the created Python code in a Python server, like Jupyter notebook to perform the ETL operations
* Verify the data import by running statements in PostgreSQL

# Structure

* Category DataFrame: Extract and transform crowdfunding categories.
* Subcategory DataFrame: Extract and transform crowdfunding subcategories.
* Campaign DataFrame: Extract and transform campaign data.
* Contacts DataFrame: Extract and transform contact information.
* Crowdfunding Database: Create a PostgreSQL database schema and import the transformed data

# 1. Create the Category and Subcategory Data Frames
* Extract data from crowdfunding.xlsx.
* Transform and create:
    * category.csv: Contains category_id and category columns.
    * subcategory.csv: Contains subcategory_id and subcategory columns.
# 2. Create the Campaign DataFrame
* Extract and transform data from crowdfunding.xlsx.
* Create campaign.csv with the following columns:
    * cf_id
    * contact_id
    * company_name
    * description
    * goal (float)
    * pledged (float)
    * outcome
    * backers_count
    * country
    * currency
    * launch_date (datetime)
    * end_date (datetime)
    * category_id
    * subcategory_id
# 3. Create Contact Data Frame:
 * Extract data from contacts.xlsx using Python dictionary methods
 * Create contacts.csv with the following columns:
    * contact_id
    * first_name
    * last_name
    * email
#  4. Create a Crowdfunding Database
  * Inspect the CSV files and create an ERD
  * Created a PostgreSQL database schema (crowdfunding_db_schema.sql)
  * Set up a PostgreSQL database (crowdfunding_db) and import the data. 
