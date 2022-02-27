# crypto-database

A database holding information about founders, investors and traits of cryptocurrencies. Can be used to find competition for certain token or search tokens by investor.

**src directory contains:**
* PostgreSQL.py - Contains class, which helps to fill data into a PostgreSQL database.
* sql_script - Script, which when executed in PostgreSQL creates tables, views, procedures and functions of the database.
* postgre_sql.ipynb - Fills data into a PostgreSQL database.


**requirements:**

* PostgreSQL version 12 
* libpq-dev
* Python version 3.9.7
* ipykernel
* psycopg2==2.8.6