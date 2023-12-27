# Python & SQL: ETL Processes with Python and SQL  

## Introduction  
Welcome to the repository for Python and SQL ETL (Extract, Transform, Load) processes! This project emerged from the need for students to practice SQL and incorporate a dataset into a simple database project. The dataset, containing information about city-district-neighborhood in Turkey, was found online. However, its format wasn't suitable for SQL, and there were duplicates. To address this, Pandas was employed to prepare the data before inserting it into a locally hosted SQL database.

## Libraries:  
Popular libraries for ETL (Extract, Transform, Load) operations with Python on SQL (namely: PostgreSQL, we used PostgreSQL in this notebook and we preferred psycopg2):

pip install psycopg2
pip install sqlalchemy
pip install pandasql
pip install pandas-gbq

## ETL Overview
ETL stands for Extract, Transform, Load, a critical process in data integration. Here's a quick overview of the ETL process:

`Extract`: Data is extracted from various sources, such as databases or files.  
`Transform`: The extracted data undergoes transformation, including cleaning, filtering, and manipulation to fit the desired structure or format.  
`Load`: The transformed data is loaded into a target system, typically a data warehouse, making it accessible for analysis and reporting.  
ETL is fundamental for ensuring data quality, consistency, and making information from diverse sources usable for analytics and decision-making in a unified manner.  

## Project Overview  

In this notebook, we executed the following steps:
1. Extracted necessary data from the web in SQL query format.
2. Used Python, primarily Pandas, to transform the data.
3. Loaded the processed data into an SQL database.
4. Extracted existing data from the SQL database to Python for necessary changes.
5. Transformed the data in Python.
6. Loaded the modified data back into the SQL database.

**Data:** The 'mahalle.csv' file was created from an SQL query found on GitHub. The format of the query wasn't suitable for the local database, and due to its length (around 50K records), processing via Pandas in Python was preferred.

Feel free to explore the code in the repository and adapt it to your own ETL projects! If you have any questions or suggestions, please don't hesitate to reach out. Happy coding!

## Contact  
For questions, collaborations, or further discussions, feel free to reach out on [Linkedin](https://www.linkedin.com/in/fatih-calik-469961237/), [Github](https://github.com/fatih-ml) or [Kaggle](https://www.kaggle.com/fatihkgg)