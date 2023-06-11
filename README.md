# Sparkify Postgres ETL

Learn about the fundamentals of data modeling and how to create a relational database using PostgreSQL. The project focuses on building an ETL (Extract, Transform, Load) pipeline to process and analyze data.

The main objectives of the project are:

Define the data schema: Students are tasked with designing the schema for a fictional startup called Sparkify, which wants to analyze the data they have been collecting on songs and user activity. The schema includes a fact table and several dimension tables, representing various entities such as users, songs, artists, and time.

Build the ETL pipeline: Students need to implement an ETL pipeline that extracts data from JSON files, transforms it to fit the defined schema, and loads it into the PostgreSQL database. This involves processing and cleaning the data, as well as executing SQL queries to insert the data into the appropriate tables.

Perform data analysis: Once the ETL pipeline is successfully implemented, students can execute SQL queries to analyze the data and answer specific questions about user activity, such as the most frequently played songs, user preferences, and other relevant insights.

I started by understanding the dataset provided, which consisted of JSON files containing information about user activity, songs, artists, and timestamps. Based on the requirements, I designed a relational data schema using PostgreSQL, creating tables that represented the different entities and their relationships.

Next, I implemented an ETL pipeline to extract the data from the JSON files, transform it into the appropriate format, and load it into the corresponding tables in the database. This involved writing Python scripts to parse the JSON files, perform data transformations, and execute SQL statements to insert the data into the tables.

Once the ETL pipeline was successfully executed, I had a fully populated database with structured data. I then used SQL queries to perform data analysis on the dataset. For example, I wrote queries to find the most active users, the most popular songs, and analyze user activity over time.

Throughout the project, I documented my design decisions, assumptions, and steps taken in a comprehensive README file. This documentation serves as a guide for others to understand the project and reproduce the results.

Overall, completing this project gave me hands-on experience in data modeling, ETL processes, and database management using PostgreSQL. I gained a deeper understanding of how to design an effective data schema, extract data from various sources, transform it for analysis, and leverage SQL for querying and data analysis. This project was a valuable opportunity to apply the concepts and techniques learned throughout the Data Engineering Nanodegree program in a real-world scenario.

python "create_tables_2.py" :

![alt text](https://github.com/adelhany1/Telecom-ETL-with_SSIS/blob/main/control%20flow.PNG)

python "etl_4.py"

![alt text](https://github.com/adelhany1/Telecom-ETL-with_SSIS/blob/main/control%20flow.PNG)
