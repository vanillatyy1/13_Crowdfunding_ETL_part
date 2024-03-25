# Crowdfunding_ETL

# Project in collaboration with [Amer B.](https://github.com/Amer4r/crownfunding_etl)

## 1) Executive Summary:

Project "Crowdfunding ETL," aims to demonstrate the extraction, transformation, and loading (ETL) process using Python, Pandas, and other relevant tools. The project involves creating structured datasets from raw Excel data files, specifically 'crowdfunding.xlsx' and 'contacts.xlsx', and exporting them into CSV files. Additionally, the project includes creating a PostgreSQL database schema based on the CSV data and importing the data into the respective tables. Through this project, we aim to showcase proficiency in data manipulation, schema design, and database management, essential skills for data analysts and business intelligence professionals.

## 2) Project Scope:

The scope of the Crowdfunding ETL project encompasses several key tasks:

- Extracting data from 'crowdfunding.xlsx' and 'contacts.xlsx' Excel files.
- Transforming the extracted data to create structured datasets, including Category, Subcategory, Campaign, and Contacts DataFrames
- Exporting the transformed data into CSV files named 'category.csv', 'subcategory.csv', 'campaign.csv', and 'contacts.csv'
- Designing a PostgreSQL database schema based on the CSV data, considering primary keys, foreign keys, and relationships
- Creating a new PostgreSQL database named 'crowdfunding_db' and implementing the schema
- Importing the CSV data into the corresponding tables within the 'crowdfunding_db' database
- Verifying the data integrity and completeness by querying the tables

## 3) Project Objectives:

The objectives of the Crowdfunding ETL project are as follows:

- Create a Category DataFrame with sequential category IDs and category titles extracted from 'crowdfunding.xlsx'
- Create a Subcategory DataFrame with sequential subcategory IDs and subcategory titles extracted from 'crowdfunding.xlsx'
- Create a Campaign DataFrame with essential campaign details extracted and transformed from 'crowdfunding.xlsx'
- Create a Contacts DataFrame with contact details extracted and transformed from 'contacts.xlsx'
- Export the Category, Subcategory, Campaign, and Contacts DataFrames as CSV files
- Design a PostgreSQL database schema incorporating appropriate primary keys, foreign keys, and relationships based on the CSV data
- Create a new PostgreSQL database named 'crowdfunding_db' and implement the schema
- Import the CSV data into the corresponding tables within the 'crowdfunding_db' database
- Verify the successful import of data by querying the tables

## 4) Resource Requirements:

The Crowdfunding ETL project requires the following resources:

- Access to the 'crowdfunding.xlsx' and 'contacts.xlsx' Excel files containing raw data
- Development environment with Python, Pandas, NumPy, and other relevant libraries installed
- Access to a PostgreSQL database server for schema creation and data import
- Sufficient disk space to store the extracted, transformed, and exported CSV files
- Collaboration tools for communication and coordination between team members, such as GitHub for version control

## 5) Takeaways:

Key takeaways from the Crowdfunding ETL project include:

- Understanding the end-to-end ETL process, from data extraction to database loading
- Proficiency in using Python and Pandas for data manipulation and transformation tasks
- Experience in designing a relational database schema and implementing it using PostgreSQL
- Knowledge of best practices for handling data extraction, transformation, and loading tasks efficiently
- Insight into the importance of data quality, integrity, and consistency in database management projects

## 6) Recommendations for Future Study:

For future study and improvement, consider the following recommendations:

- Incorporate data visualization and reporting tools to analyze and present insights derived from the database
- Collaborate with domain experts to understand more complex data transformation and cleansing techniques to handle real-world data challenges effectively

