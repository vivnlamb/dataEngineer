# dataEngineer
A project to apply data analysis to data engineering - using Python/SQL to migrate data

Project outline: ETL vs ELT?
1. Cloud DataBase: Create SnowFlake account, query against DB
2. Data: load interesting dataset (Kaggle, huggingface) into SnowFlake database.
3. Jupyter Notebook: import data from SnowFlake, EDA, propose problem / solution based on trends
4. API: write function, write API for function using fastapi to do some Transform
5. GIT: clone to GitLab, set automation to run the code on interval
6. Tableau: visualize data
7. profit and retire

ETL process: pipeline
- run code/data
- transform
- move code/data

Extract: 
- load.csv
- SQL Alchemy connect to DB, read, write to DB

Transform: 
- pandas dataframes
- clean data, etc.

Load:
- dbt
- SQL Alchemy
