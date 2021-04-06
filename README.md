# E-Commerce_Database-Analyst
E-commerce Database Analysis

# DATASET:

The dataset is from an online retailer using in-house server hosting for their website. They have multiple new products launched and I will derive insights into how well they're website is driving sales. The dataset I'll be using is comprised of three years worth of data, however, I'll be drilling down into just the first year's performance.

I'll be working with three related tables, which contain eCommerce data about:

•Website Activity
•Products
•Orders

The tables and thier contents can be viewed at this link: https://user-images.githubusercontent.com/81595198/113777828-7aae0e00-96e0-11eb-8aba-fdf9243a5d47.PNG

# Tools:

•PgAdmin
•PostgreSQL
•Tableau

# Installation:

1. Go to www.postgresql.org and click on the 'Downloads' Tab to download the appropriate version for your OS.
2. Run the installer for PostgreSQL leaving all the compenents checked and be sure to remember the password you create once prompted. (Uncheck 'Launch Stack Builder'.)
3. Go to www.pgadmin.org and click on the 'Downloads' Tab to download the latest version for your OS. Run the installer. Once complete, restart your computer.
4. Launch PgAdmin and when prompted to enter a password for your PostgreSQL version use the password created earlier.

Note: The upcoming steps involve downloading the CSV files located in this repository and importing them into PgAdmin. Currently, there is no automated way to import these files without first creating the tables for the data. The following instructions entail creating the tables first through a SQL Query then importing the CSV files into those tables.

1. Click on the Postgresql version downloaded (top right corner) and select 'Create'--> 'Database...' and name your database when prompted.
2. Click on the newly created database and select 'Query tool...' to create your table. The name of the table and columns are provided from the link above.
3. Expand your created database and expand the 'Schemas' tab, then expand the 'public' schema to find your created tables.
4. Download the datasets from the repository and copy the file path. (This will be used as the 'filename' for your 'Import/Export' prompt in PgAdmin.)
5. Right click on your created table and select 'Import/Export...'.
6. Paste the copied filepath in the filename prompt. 
7. Uncheck 'header' as 'No' since no header is included in the CSV, and delimiter as ',' since its a CSV.
8. Click 'OK' to complete the import and repeat for the remaing tables.
